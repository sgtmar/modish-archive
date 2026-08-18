# Modish Archive Repository Instructions

## Collection data

- Treat `collection.json` as the master database for the Modish Archive collection.
- Preserve all existing collection records unless the user explicitly requests a change.
- After every edit to `collection.json`, validate that the complete file is valid JSON.
- Never alter pricing, grades, variants, notes, inventory totals, valuation totals, or related fields unless the user explicitly instructs you to do so.
- Keep `index.html` compatible with the structure and fields in `collection.json`.

## Change review

- Review the complete Git diff before committing.
- Confirm that the diff contains only the requested changes.
- Stage and commit only the intended files and changes.
- Never include unrelated files or content from elsewhere on the user's computer.
- If an unexpected or unrelated change is present, stop and ask the user before proceeding.

## Publishing

- Push repository updates only to `origin/main` and only when the user has authorized the push.
- Do not push to any other remote or branch.
- After pushing, confirm the full commit SHA and verify that the working tree is clean and synchronized with `origin/main`.
