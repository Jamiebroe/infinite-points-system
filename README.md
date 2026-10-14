# Infinite Points System — SillyTavern UI Extension

A clickable, chat-specific fictional points ledger and shop. Supports manual reward categories, stats, inventory, transaction history, and JSON import/export.

## Hosted installation

A ZIP file cannot be directly installed through SillyTavern's **Install Extension** menu. Upload the contents of this directory to a GitHub repository (manifest.json at repository root), then use **Extensions → Install Extension** with the repository HTTPS URL. Your hosted provider must allow user extensions and Git installation. If they disable it, ask the host administrator; a browser-only user cannot force server installation.

## Use

Click **✦ System** at bottom right. Data is stored in SillyTavern's per-chat metadata. Reward buttons require manual approval; no automatic parsing of roleplay messages is implemented. Shop purchases deduct points and increment inventory. Stats are manually adjusted. Use Settings to edit shop/rewards and export a backup.

## Caveats

- This is an untested starter extension; compatibility may depend on host version and policies.
- Lorebook World Info is separate and should be imported and enabled independently.
- The extension does not inject its data into the AI prompt. For accurate narrative consistency, copy or summarize relevant state in your Author's Note.
- The UI is visible to the human using the browser; fictional characters cannot see it within the story.
- Do not store real sensitive personal information in this extension's state.
