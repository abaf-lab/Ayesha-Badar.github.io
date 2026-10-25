# Troubleshooting: Reports Won't Export

> **Sample document.** This guide is written for a fictional product ("Acme Analytics") to demonstrate structure, tone, and troubleshooting design. It is not based on any employer's content.

**Applies to:** Acme Analytics web app, all plans
**Last reviewed:** [date]
**Owner:** [team]

## Symptom

You select **Export** on a report, but no file downloads, or you see the message "Export failed."

## Before you start

- You need **Viewer** access or higher on the report.
- Exports are limited to 100,000 rows per file.

## Quick checks

1. Confirm the report finished loading (no spinner in the top-right corner).
2. Try a different export format (CSV instead of XLSX).
3. Open the report in a private browser window to rule out extensions.

## Causes and fixes

| Cause | How to tell | Fix |
|---|---|---|
| Report exceeds the row limit | Banner reads "Too many rows" | Add a filter or date range, then export again |
| Browser is blocking downloads | No prompt appears; download icon shows a block | Allow downloads for the Acme domain in browser settings |
| Missing permission | Export button is disabled | Ask the report owner for Viewer access or higher |
| Temporary service issue | Error persists across browsers and reports | Check the status page, then try again later |

## If the problem continues

Contact support and include:

- The report name and URL
- The export format you chose
- The exact error message
- Your browser and version

## Related articles

- Export limits and file formats
- Manage report permissions
