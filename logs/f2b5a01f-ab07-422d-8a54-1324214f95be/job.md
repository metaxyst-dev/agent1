Test the bookkeeping agent capabilities by performing a sample financial reconciliation workflow.

Tasks to complete:

1. Create sample financial documents in a test directory:
   - Generate a mock invoice (vendor: "Office Supplies Inc", amount: $245.67, date: current month)
   - Generate a mock bank statement entry for the same transaction
   - Create a sample quote that could convert to an invoice

2. Test the new bookkeeping skills:
   - Use invoice-parser.js to extract data from the mock invoice
   - Use statement-reconciler.js to match the invoice against the bank statement
   - Use quote-analyzer.js to process the sample quote
   - Use financial-reporter.js to generate a reconciliation summary

3. Verify the reconciliation workflows:
   - Follow the RECONCILIATION.md process step by step
   - Test the INVOICE_REVIEW.md workflow with the mock invoice
   - Document any issues or improvements needed

4. Generate a test reconciliation report showing:
   - Successfully parsed invoice data
   - Matched transactions between invoice and statement
   - Summary of reconciliation results
   - Any discrepancies or items requiring attention

5. Save all test results to logs/ directory for review

This test will validate that the bookkeeping agent can properly handle financial document processing and reconciliation tasks.