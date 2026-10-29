# Cyber Fraud PDF Data Extractor & BNSS 94 Notice Generator

A lightweight, purely client-side web application designed for Cyber Cell and Police Investigation Units. It extracts transaction details and suspect bank accounts from **1930 National Cyber Crime Reporting Portal** PDF reports and automatically generates standardized statutory notices under **Section 94 of Bharatiya Nagarik Suraksha Sanhita (BNSS), 2023**.

## Features

- **Client-Side PDF Parsing:** Uses `pdf.js` to process case documents locally without uploading sensitive data to any server.
- **Automated Trail Extraction:** Auto-detects Complainant info, Acknowledgement No, Bank Name, Account Numbers, IFSC codes, and Transaction IDs/UTRs.
- **BNSS 94 Notice Generation:** Automatically formats individual, single-account A4 printable notices per bank/beneficiary account.
- **Print Ready:** Optimized print styles (`@page` setup) designed strictly for standard A4 printing.

## Tech Stack

- HTML5
- Tailwind CSS & W3.CSS
- Vanilla JavaScript
- PDF.js (Mozilla)
- FontAwesome Icons

## Deployment

Hosted directly via **GitHub Pages**.

## License

Internal Law Enforcement / Cyber Investigation Tool."# kyc-report-generator" 
