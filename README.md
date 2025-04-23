# Financial Document Analyzer

A privacy-focused budgeting and financial insight tool built with [Next.js](https://nextjs.org/) (App Router) and [TypeScript](https://www.typescriptlang.org/). This app allows users to upload PDF bank and credit card statements, extract and categorize transactions, and view clear expense vs income summaries.

## Tech Stack

-   [Next.js 15](https://nextjs.org/) (App Router)
-   [TypeScript](https://www.typescriptlang.org/)
-   [Tailwind CSS](https://tailwindcss.com/)
-   [ESLint](https://eslint.org/)
-   [PDF Parsing](planned with `pdfplumber`, `PyMuPDF`, or similar)

## Features (Planned & In Progress)

-   Upload PDF bank/credit card statements
-   Extract transactions: date, description, amount
-   Display transactions in a table
-   Categorize transactions (rules + manual tagging)
-   Detect credit card payments and internal transfers
-   Generate budgets and visualize income vs expenses
-   User-defined categories and rules

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/financial-analyzer.git
cd budgetapp
```

### 2. Install Dependencies

```bash
npm install
# or
yarn
```

### 3. Run the dev server

```bash
npm run dev
# or
yarn dev
```

Then visit [localhost](http://localhost:3000) in your browser.

## Project Structure

```bash
src/
├── app/               # App router layout and routes
├── components/        # Shared UI components
├── lib/               # Utility functions, parsing helpers
├── styles/            # Tailwind config and globals
├── types/             # TypeScript type definitions
└── ...

```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

If you have any questions or suggestions, please feel free to reach out:

-   **GitHub:** [CDChamberlin](https://github.com/CDChamberlin)
