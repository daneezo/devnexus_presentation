# CSV Data Cleaner Prompt

Use this prompt with Google Apps Script via ChatGPT or Claude to clean messy spreadsheet data.

## The Prompt

```
You are a Google Apps Script expert. Write a function called cleanCSVData() that:

1. Reads data from the active sheet starting at row 1
2. Trims leading/trailing whitespace from all cells
3. Standardizes name casing to Title Case
4. Normalizes email addresses to lowercase
5. Parses dates in any format (MM/DD/YYYY, "March 5 2024", YYYY-MM-DD, etc.) into YYYY-MM-DD
6. Removes exact duplicate rows (match on name + email)
7. Standardizes status values: map "Active", "ACTIVE", "active" → "Active"; "Churned", "CHURNED" → "Churned"; "Trial", "TRIAL" → "Trial"
8. Strips dollar signs and commas from numeric fields
9. Formats phone numbers to (XXX) XXX-XXXX
10. Highlights rows that had issues in light yellow

Write the complete script. Add comments explaining each transformation step.
Output the cleaned data to a new sheet called "Cleaned".
```

## Why This Works

This prompt follows the **Build → Test → Iterate** pattern:
- **Role**: "Google Apps Script expert" sets the context
- **Procedure**: 10 numbered, specific steps (not vague)
- **Constraints**: Specific format targets (YYYY-MM-DD, Title Case, etc.)
- **Output format**: New sheet called "Cleaned"

## The Bad Prompt (for comparison)

```
Clean up the data in my spreadsheet
```

This fails because it gives AI no context about what "clean" means, what format you want, or what tool to use.
