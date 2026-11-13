# Max Docs

AI-assisted DOCX workspace built for GitHub Codespaces and 9Router.

## Features
- Import DOCX and extract editable text.
- Edit document text in the browser.
- Use a 9Router-compatible chat-completions model to rewrite content.
- Export edited text as a new DOCX file.
- API credentials stay on the server.

## Run in Codespaces
Run `npm install`, copy `.env.example` to `.env`, configure `AI_BASE_URL`, `AI_API_KEY` and `AI_MODEL`, then run `npm run dev`. Open forwarded port 5173.

## DOCX compatibility
This first milestone extracts document text and generates a new DOCX. It does not preserve original Word layout, styles, images, headers, footers or complex tables. Format-preserving SuperDoc integration remains a follow-up milestone.
