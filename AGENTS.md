# Repository Guidelines

## Project Structure & Module Organization

- `00-Introduction/`, `01-Part_One/`, `02-Part_Two/`, `03-Part_Three/`, `04-Part_Four/`, `05-Appendix/` hold the book’s chapters and appendices as Markdown.
- Top-level `.md` files are front/back matter (e.g., `Glossary-*.md`, `Conclusion-*.md`).
- `assets/` contains shared images referenced by Markdown (e.g., `assets/Agentic_Design_Patterns_Book_Cover.png`).

## Build, Test, and Development Commands

- No build or test scripts are defined in this repo.
- If you generate artifacts locally (e.g., PDFs), keep them out of version control unless explicitly requested.

## Content Style & Naming Conventions

- Content is Markdown-first; keep headings consistent and preserve existing structure.
- File naming follows a numbered prefix and a stable ID suffix, e.g., `01-Part_One/Chapter_1-Prompt_Chaining-<id>.md`. Do not rename existing files unless requested.
- When adding new content, mirror the directory naming pattern and keep image paths relative, e.g., `../assets/<image>.png`.

## Testing Guidelines

- No automated tests are present.
- Verify edits by checking Markdown rendering and image links locally.

## Commit & Pull Request Guidelines

- Recent commits use short, imperative messages, sometimes prefixed with a type (e.g., `chore: Minor fixes to formatting and naming`, `Add Glossary file with index of terms definitions`). Follow this style.
- PRs should describe what changed and why, and link to any related issue or request. Include screenshots only when visual assets are updated.

## Contribution Notes

- This repository is a curated book text; prioritize accuracy and formatting stability.
- Avoid bulk formatting changes unless explicitly requested.
