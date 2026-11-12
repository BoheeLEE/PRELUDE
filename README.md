# PRELUDE Study website

## Which file is which tab

| Tab | File to edit |
|---|---|
| About | `index.md` |
| Team | `team.md` |
| How to get involved | `get-involved.md` |
| PPIE | `ppie.md` |
| News & Publications | `news.md` |
| Contact | `contact.md` |
| Footer (funding text) | `_config.yml` |
| Menu order and names | `_data/navigation.yml` |

You only need to edit the files above. Leave `_layouts` and `assets` alone.

## How to edit
1. Open the file on GitHub and click the pencil icon.
2. Change the text. Keep the block between the two `---` lines at the top (it sets the page title).
3. Click **Commit changes**. The site updates in about 1 minute.

## Settings at the top of some pages
- `index.md` → `goals:` the three goal cards on the home page
- `get-involved.md` → `form_url:` paste a Microsoft Forms link to show the sign-up form
- `news.md` → `upcoming:` and `items:` the news list. Each item's `type` must match one of `types:` (Papers, Presentations, Engagements, News) for the filter buttons to work

In these lists, keep the spaces at the start of each line exactly as they are.

## Writing tips (Markdown)
- `## Heading` makes a section heading, `### Heading` a smaller one
- `**bold**`, `*italic*`
- `- item` makes a bullet point
- `[link text](https://example.com)` makes a link
- A line starting with `>` makes a highlighted box
- Search for `TODO` to find all yellow placeholders
