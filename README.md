# Software Development Practices Survey

A web-based survey on software development practices and methodology selection in startups. Built as a static HTML site hosted on GitHub Pages.

## About

This survey collects structured data from startup founders, developers, and team leads on topics including:

- Startup profile and domain
- Technical stack and development process
- Organizational readiness
- Business context and market environment
- Incubation center influence
- Challenges and adaptation
- Future orientation and AI adoption

Estimated completion time: 10–15 minutes. All responses are confidential.

## Structure

```
index.html      # The survey (single self-contained file)
README.md       # This file
```

## Hosting

Deployed via GitHub Pages at:
```
https://noorulainpatoli.github.io/survey.html/
```

## Usage

Open the live URL and complete the survey section by section. Required fields are marked with an asterisk (*). Navigation is linear — use the Back and Next buttons to move between sections.

## Sections

| Section | Topic |
|---------|-------|
| Consent | Participant consent |
| A | Startup Profile |
| B | Technical & Process Environment |
| C | Organizational Readiness |
| D | Business Context & Market Environment |
| E | Incubation Center Influence |
| F | Challenges, Learning & Adaptation |
| G | Future Orientation & Innovation |
| H | Closing & Reflection |

## Notes

- No backend or database is connected. To collect responses, integrate with Google Sheets via Apps Script or a service like Formspree.
- The survey is fully client-side — no data leaves the browser unless a submission endpoint is configured.
