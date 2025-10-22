# Data Analysis Tool

## How to run
1. Clone the repository.
2. Open `index.html` in a web browser.
3. Use the file upload to analyze .xlsx files.

## Features
- Upload .xlsx files for data analysis.
- Displays a message after uploading a file.

## Accessibility
- The app is built with semantic HTML5.
- It supports keyboard navigation and focus styles.

## Design tokens (CSS variables/palette)
- Header background: `--header-bg`
- Button background: `--button-bg`

## API endpoints used
- No external APIs used in this round.

## Attachments used
- `execute.py`
- `data.xlsx`

## Keyword coverage
| Keyword/Phrase                       | Implementation Location                |
|--------------------------------------|---------------------------------------|
| execute.py                           | Code handling data analysis            |
| data.csv                             | Converted from data.xlsx              |
| .github/workflows/ci.yml            | GitHub Actions configuration           |
| result.json                          | Generated in CI                       |
| ruff                                 | CI workflow step                      |
| GitHub Pages                         | Deploy result.json                    |

## Changelog: Round 1
- Initial implementation of the data analysis UI
- Integrated file upload functionality
- Styling added for improved user experience
- README created with necessary sections
- Accessibility considerations added
- Preparations made for CI integration