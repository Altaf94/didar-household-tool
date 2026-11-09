# Didar Household Tool

A local utility for Didar event registrations: search households, view family members and approve registrations.

## Context

Talks to the registration API used by the event portal. It includes a React web UI and a Python command-line tool.

## Features

- Search households by Form ID or CNIC
- View household information and family members
- Approve family member registrations
- Python CLI that uses the same API (`didar_household_tool.py`)

## Tech stack

- **Web:** React, Vite, React Router
- **CLI:** Python 3, requests

## Getting started

```bash
npm install && npm run dev        # web UI
python3 didar_household_tool.py   # CLI (see config.example.json)
```

## Screenshots

<!-- Add 2-3 screenshots here: docs/screenshots/*.png -->

## Notes

- Tokens and config go in `config.json` or environment variables. Never commit them.

## Author

Built by **Altaf Hassan**, Software Engineer (React Native & full-stack). [Portfolio](https://altaf94-portfolio.netlify.app) · [LinkedIn](https://linkedin.com/in/altaf-hassan)
