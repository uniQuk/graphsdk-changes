# Graph SDK Changes Monitor

This repository contains auto-generated reports that track changes to the Microsoft Graph API. These reports are automatically updated whenever changes are detected in the Microsoft Graph SDK.

## Latest Report

**Latest report:** [2025-03-11_224008](./latest/)

<!-- SUMMARY_PLACEHOLDER -->

# Microsoft Graph API Change Report

## Summary Report Graph SDK Changes
Generated on 2025-03-11 22:40:08

### Overall Statistics
- **Total Cmdlets**: 0
- **Total Endpoints**: 0
- **Total Scopes**: 0
- **Total Cmdlet Changes**: 23754
- **Total Endpoint Changes**: 21138
- **Total Scope Changes**: 351

### Detailed Statistics by Version

#### v1.0
- Cmdlet Changes: Added: 0, Removed: 9086, Modified: 0
- Endpoint Changes: Added: 0, Removed: 8163, Modified: 0

#### beta
- Cmdlet Changes: Added: 0, Removed: 14668, Modified: 0
- Endpoint Changes: Added: 0, Removed: 12975, Modified: 0

#### scopes
- Scope Changes: Added: 0, Removed: 351, Modified: 0


---



## Repository Structure

```
/
├── reports/
│   ├── YYYY-MM-DD_HHMMSS/   # Timestamped reports
│   │   ├── cmdlets.md       # Changes to cmdlets
│   │   ├── endpoints.md     # Changes to endpoints
│   │   ├── scopes.md        # Changes to permission scopes
│   │   └── summary.md       # Combined summary of all changes
│   ├── ...
│   └── latest/              # Symbolic link to most recent report
```

## Understanding the Reports

Each report folder contains four Markdown files:

1. **`summary.md`**: A high-level overview of all changes detected, including totals of added, removed, and modified elements
2. **`cmdlets.md`**: Detailed changes to PowerShell cmdlets in the Graph SDK
3. **`endpoints.md`**: Detailed changes to API endpoints in the Graph SDK
4. **`scopes.md`**: Changes to permission scopes required for various operations

## Change Categories

Changes are organized into three categories:

- **Added**: New cmdlets, endpoints, or permission scopes that weren't present in the previous version
- **Removed**: Elements that existed in the previous version but have been removed
- **Modified**: Existing elements that have had their properties or behavior changed

## Monitoring Changes

The `latest` directory always points to the most recent change report. To stay updated with changes to the Microsoft Graph API:

1. Watch this repository to receive notifications when new reports are generated
2. Check the `latest` folder for the most up-to-date changes
3. Browse historical reports by their timestamped folders to see how the API has evolved over time

## Automation

These reports are generated automatically by a change detection system that monitors the Microsoft Graph SDK. New reports are published whenever changes are detected in the underlying API structure.

## Additional Resources

- [Microsoft Graph API Documentation](https://learn.microsoft.com/en-us/graph/overview)
- [Microsoft Graph PowerShell SDK](https://learn.microsoft.com/en-us/powershell/microsoftgraph/overview)

---

*This repository is maintained automatically by a GitHub Action workflow.*