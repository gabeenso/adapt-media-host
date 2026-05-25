# Public repo rules

This repo is **public**. Anything committed is world-readable forever — Git history can't be scrubbed without a force-rewrite.

**Purpose:** Public host for video assets that Buffer needs to fetch by URL. Files here are referenced by adapt-content's buffer_push.py via GitHub release assets.

## Allowed
- Released video files (uploaded as release assets, not committed to the tree)
- README explaining the host's role

## Banned (no exceptions)
- `.env`, API keys, tokens, OAuth secrets, webhook URLs with secrets
- Client names, email addresses, phone numbers, contact lists
- Revenue figures, pricing models, valuation work, financial projections
- Charter Partner Agreements, proposals, internal contracts
- Brand strategy docs, unreleased frameworks, IP that's not shipped
- Drafts of any content — public = already published only
- Anything from Adapt's internal docs, Notion, or Drive

**If you're not sure, it doesn't go here.**
