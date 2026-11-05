# Kajiado North Citizen Tracker

A mobile-first, plain-English, **independent civic research** website. It contains 89 project/programme register entries and 11 historical audit findings from a working research register.

## Interpreting the headline
- **43 of 57 current-term entries** are approved records (FY2022/23, FY2023/24) for which downstream status is not confirmed by this research. That is a **documentary gap**, NOT a claim that 43 projects failed.
- **32 inherited entries** predate the current MP. This is a record classification, not a finding of wrongdoing.
- **3 audit entries** are pending stronger primary-source checks. Don't describe them as established findings before verification.
- Audit figures are associated amounts, **not established losses**.

## Website
This is a static HTML/CSS/JS website for GitHub Pages. Load `index.html`. Assets and data are embedded/fallback-ready to support download and local use. Project details, search, record links, ward filters and audit filters should work on an HTTPS deployment.

Citizen observations are private localStorage drafts. They are never sent anywhere or publicly uploaded.

**Not an official NG-CDF or Office of the Auditor-General website.** Historical funding responsibility must be validated before any claim about the current office-holder.

## To maintain
Update the source register in `data.json`, the corresponding embedded copy in `index.html`, and CSV exports together. Check content, privacy, and source documents before publishing new claims.