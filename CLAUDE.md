# Financial Analysis Repository

## Purpose
This repository contains independent equity research. Each company under coverage has a dedicated folder in `Coverage/` with the full investment thesis, supporting analysis, and source filings.

## Directory Conventions
- `Coverage/` contains all evaluated companies, one subfolder per ticker
- `Coverage/TICKER/` is the blank template; copy it for new coverage
- Each company folder follows the same structure: analysis files, `Earnings/` for quarterly updates, `filings/` for source documents, and a `README.md` as the final report
- The root `README.md` is the landing page with the coverage universe index

## Research Rules
- Base all factual claims on documents in the company's `filings/` directory
- Citation format: `[filename, page/section]: "exact quote" -> interpretation`
- For unsourced claims: state "Not found in available filings"
- Never fill gaps with training data or general knowledge
- If a number cannot be verified from filings, say so explicitly
- Prefer the most recent filing period; flag older data with its period
- Mark inferences as "(inferred from [source])"; never present inferences as facts

## Analysis Sequence
For each new company, work through these files in order:
1. Business Overview
2. Industry Scan
3. Financial Deep Dive
4. Moat Analysis
5. Management Review
6. Valuation Check
7. Bear Case
8. Compile the README.md investment thesis from all findings
9. Decision Log entry when making investment decisions

## Output Standards
- Clear headers, short paragraphs, plain English
- Use tables for comparative data
- Every metric must include its source filing and period
- No em dashes or double hyphens in text; use "to" for ranges (e.g., "$55 to $65")
- Professional, portfolio-manager-facing tone

## Formatting Rules
| Pattern | Replacement |
|---------|-------------|
| Em dash in text | Comma, semicolon, parenthesis, or restructure sentence |
| Double hyphen for ranges | "to" (e.g., "$55 to $65", "2024 to 2025") |
| Empty table cell | "N/A" |
| Horizontal rule | `***` or omit |

## Root README Maintenance
When a new company report is completed or an existing report is updated:
1. Update the Coverage Universe table in the root `README.md`
2. Include: ticker, company name, recommendation, fair value, report date, and link to the report

## Hard Rules
- NEVER fabricate numbers or use placeholder data
- NEVER present training knowledge as company-specific facts
- NEVER skip citation requirements in analysis files
- If data is insufficient for a section, state what is missing and what filings would resolve it
