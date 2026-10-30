# FarmFusion QA Testing

Manual QA testing of **FarmFusion**, my final year project: a web app (also usable on mobile screens) for managing livestock.

**App link:** https://farm-fusion-manage.vercel.app/login

## About the app
After signing up and logging in, a user reaches a dashboard where they can:

- Buy and sell animals in a cattle market
- Track the progress of animals they bought
- Manage vaccinations for their animals
- Track breeding, including expected birth dates
- Set up their cattle farm and animal types in settings: cows, bulls, sheep, goats and camels

## Project status
**In progress.** The test plan is complete. Test cases and bug reports are being added module by module, and this README will be updated with real results as testing is finished.

## What I am doing
- Writing a **test plan** covering scope, approach, environment and exit criteria
- Writing and executing **test cases** (positive, negative and boundary) for every module
- Reporting every failed test case as a **bug report** with steps to reproduce, expected and actual results, severity and a screenshot

## Modules covered
| Module | What is tested | Planned test cases |
|---|---|---|
| Sign Up | Valid, invalid, empty and duplicate registration | 4 |
| Login | Valid and invalid credentials, logout, session | 5 |
| Dashboard | Page load, summary, navigation | 3 |
| Cattle Market | Buying and selling animals, price and quantity limits | 8 |
| Animal Progress | Progress of bought animals, updates | 4 |
| Vaccination | Vaccination records, due dates, edit and delete | 5 |
| Breeding | Breeding records, expected birth dates | 5 |
| Settings | Cattle farm details, animal types | 6 |
| UI / Compatibility | Mobile view, browsers, layout | 4 |
| **Total (approx.)** | | **44** |

## Results
Results will be added here after execution:

- Test cases executed: to be updated
- Passed: to be updated
- Failed: to be updated
- Bugs reported: to be updated

## Repository structure
- **README.md**: project summary
- **test-plan/**: test plan (PDF)
- **test-cases/**: test cases with results (Excel and CSV)
- **bug-reports/**: bug reports and a template
- **screenshots/**: evidence for each bug

## Testing details
- **Type:** manual functional, negative, boundary, UI and basic security testing
- **Tools:** Excel / Google Sheets, browser developer tools, GitHub
- **Browsers:** Chrome, Edge, Firefox

## Author
**Muhammad Ali Khan**
Aspiring SQA Engineer | Karachi, Pakistan
GitHub: https://github.com/makaic18-sudo/FarmFusion-SQA
Email: makaic18@gmail.com
