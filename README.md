# billcom-upload-prep

Makes an AI Club reimbursement PDF Bill.com-ready. Runs entirely in the browser.

**Use it:** https://samantha-flaim.github.io/billcom-upload-prep/

1. Drop in the member's WGA SBC Reimbursement / Invoice Form PDF (form plus receipts).
2. Fix anything flagged, add a bill description, and check the approval note.
3. Download the new PDF and upload it in Bill.com's **Enter a bill**.

The tool adds a summary page in front of the member's form and receipts. Bill.com reads that page to fill in the vendor, invoice number, dates, amount, notes, and each line's account and class.

Everything happens in your browser: the PDF is never uploaded anywhere. The page is a single file (`index.html`) that loads pdf.js and pdf-lib from public CDNs.
