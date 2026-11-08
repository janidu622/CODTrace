# CODTrace
**CODTrace | Cash-on-Delivery Payment Checker**  
Independent full-stack project

- Built an app that compares order spreadsheets with two courier payment CSV formats and flags underpayments and missing payouts for Sri Lankan online sellers.
- Prevented repeat uploads from counting payments twice, linked discrepancies to their original spreadsheet rows, and sent unclear matches to a manual review queue.
- Benchmarked order-ID matching alone against a method that also checks dates and amounts when IDs are missing. Used a separate set of sample records with known answers to count correct matches, wrong matches, and cases needing review.

**Stack** · TypeScript, Next.js, NestJS, PostgreSQL, Docker, GitHub Actions, Playwright
