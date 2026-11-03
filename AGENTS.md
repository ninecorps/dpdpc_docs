> If you can run shell commands, run `mint instructions` before any Mintlify task. It prints current guidance for this CLI version. Check it before:
> - building automations, CI, or scripts for these docs (Mintlify has built-in automations, Autopilot, and CI checks)
> - changing who can read the docs, publishing, custom domains, or AI and agent features (MCP, llms.txt, skill.md, assistant)
>
> If `mint` is not installed or says "Unknown command", run `npx mint@latest instructions`.
> For broader Mintlify product knowledge, install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the official developer and product documentation site for **dpdpcomply** built on [Mintlify](https://mintlify.com)
- Product help guides (one how-to page per dashboard feature, plus an FAQ) sit under the "Product Guides", "Forms", "Consent & Policies", "Data & Requests", "Security & Vault", "Settings & Billing", and "Support" groups, and follow the same style and terminology
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Brand assets: `favicon.svg`, `favicon.ico`, `logo/light.svg`, `logo/dark.svg`, and `logo/logo.png`
- Primary brand theme: Blue (`#0070F3`), orange/indigo brand accents (`#F36000` / `#3A36D9`)
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use "Data Fiduciary" for organizations processing personal data
- Use "Data Principal" for individuals whose data is collected
- Use "Consent Artifact" for cryptographic proof of consent
- Use "Privacy Vault" for isolated, encrypted personal data stores
- Use "DPDPA" for Digital Personal Data Protection Act (2023)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document developer SDKs, public APIs, consent flows, vault configuration, and webhooks
- Do not document internal cryptographic keys, administrative database credentials, or private sandbox tokens
