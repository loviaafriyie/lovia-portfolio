# Lovia Afriyie — Professional Portfolio

A professional portfolio for **Lovia Frimpomaa Afriyie**, based in Oman, showcasing her background in customer support, sales operations and administration, along with clearly labelled independent practice projects.

**Live website:** https://lovia-portfolio.vercel.app/

## What is included

- `index.html` — homepage, including a **View my resume** link that scrolls to the resume selection section
- `style.css` and `script.js` — existing website styling and interactions
- `assets/` — Lovia's portrait
- `projects/` — independently created practice examples (not client work)
- `resumes/` — five tailored resumes in PDF and editable DOCX formats
- `vercel.json` — existing Vercel configuration

## Resume options

| Career focus | PDF | Editable Word |
| --- | --- | --- |
| Customer Support & Sales | [PDF](resumes/Lovia_customer-support-sales.pdf) | [DOCX](resumes/Lovia_customer-support-sales.docx) |
| Virtual Assistance & Administration | [PDF](resumes/Lovia_virtual-assistant.pdf) | [DOCX](resumes/Lovia_virtual-assistant.docx) |
| CRM & Sales Operations | [PDF](resumes/Lovia_crm-sales-operations.pdf) | [DOCX](resumes/Lovia_crm-sales-operations.docx) |
| Content Writing | [PDF](resumes/Lovia_content-writing.pdf) | [DOCX](resumes/Lovia_content-writing.docx) |
| Digital Marketing & Social Media | [PDF](resumes/Lovia_digital-marketing.pdf) | [DOCX](resumes/Lovia_digital-marketing.docx) |

## Deployment

This is a static site. Upload the **contents of this repository package** directly to the GitHub repository root (so `index.html` is at the top level). Vercel should be connected to the `main` branch, with **Root Directory** set to `./` and **Framework Preset** set to `Other`.

Every commit to `main` triggers a new deployment when GitHub integration is enabled.

## Updating a resume

1. Edit the relevant `.docx` in `resumes/`.
2. Export the edited document as a PDF with **exactly the same PDF filename**.
3. Replace the corresponding `.pdf` and `.docx` in GitHub's `resumes/` directory.
4. Commit to `main`; Vercel redeploys automatically. No homepage edit is needed if filenames remain unchanged.

## Notes

The project examples are fictional practice scenarios. Employment history, skills and credentials should be checked with Lovia before using the resumes in applications. Do not upload identity documents or private records to this public repository.
