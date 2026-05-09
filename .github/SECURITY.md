# Security Policy — Kntro-Soft

## Covered Repositories

This policy applies to all repositories under the **Kntro-Soft** organization on GitHub:

| Repository                 | Description                             |
|----------------------------|-----------------------------------------|
| `Kntro-Soft/ReqsAI-Report` | Academic report for the Reqs-AI project |

## Supported Versions

| Report Version      | Actively Supported             |
|---------------------|--------------------------------|
| 2.x (`main` branch) | Yes                            |
| 1.x                 | No (historical reference only) |

## Reporting a Vulnerability or Privacy Issue

If you find sensitive information accidentally exposed in this repository (credentials, personal data of interviewees, confidential client information), **do not open a public Issue**.

### How to Report

Send an email to:

**Jhosepmyr Gutiérrez Soto** — `jhosepmyrgutierrezsoto@gmail.com`

Include in your email:
- Description of the issue found
- File path or section of the repository where it is located
- Screenshot or evidence (if applicable)

### Response Time

We commit to responding within a maximum of **72 hours** and resolving the issue within **7 business days**.

## Repository Security Practices

- Do not commit credentials, tokens, or API keys in any file
- Interview recordings are not stored in the repository (only public screenshots)
- Images of individuals in `assets/` are covered by informed consent from the interviewees
- The `.gitignore` excludes exported files (`*.pdf`, `*.docx`, `*.mp4`)
