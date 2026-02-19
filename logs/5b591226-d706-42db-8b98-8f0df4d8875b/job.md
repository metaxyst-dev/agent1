Create a specialized bookkeeping agent by customizing thepopebot's operating system files. The agent should be capable of reviewing invoices, quotes, and statements to reconcile financial records.

Tasks to complete:

1. Update operating_system/SOUL.md to define the bookkeeping agent's identity:
   - Professional accounting personality
   - Expertise in financial document analysis and reconciliation
   - Attention to detail and accuracy focus
   - Knowledge of bookkeeping principles and standards

2. Create new skills in .pi/skills/ for financial document processing:
   - invoice-parser.js - Extract key data from invoice files (vendor, amount, date, items)
   - statement-reconciler.js - Compare transactions against bank/credit statements
   - quote-analyzer.js - Process quotes and track quote-to-invoice conversion
   - financial-reporter.js - Generate reconciliation reports and summaries

3. Set up document processing capabilities:
   - Configure file handling for common formats (PDF, CSV, Excel)
   - Create templates for standardized financial data extraction
   - Set up validation rules for data accuracy

4. Create example workflows in operating_system/:
   - RECONCILIATION.md - Step-by-step reconciliation process
   - INVOICE_REVIEW.md - Invoice validation and processing workflow
   - MONTHLY_CLOSE.md - End-of-month reconciliation procedures

5. Update operating_system/CRONS.json to include:
   - Daily invoice processing check
   - Weekly reconciliation reminder
   - Monthly financial summary generation

The agent should be able to work with locally stored financial documents and maintain organized records while following standard bookkeeping practices.