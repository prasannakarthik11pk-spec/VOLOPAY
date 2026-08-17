# PulseDesk — Friends of Finance Task 3

Alternative implementation for the Community Activity CRM assignment.

## What changed
This version uses a different product name, visual identity, navigation labels, fictional member dataset, activity mix, ownership names, state thresholds, and AI-assisted workflow from the reference implementation.

## Included
- Community pulse dashboard
- 15 fictional members
- Member directory with search and state filter
- Add/update member records
- Activity logging and member history
- Follow-up queue
- New arrivals, highly engaged, and needs-attention views
- Activity-based state rules
- Owner and next-action fields
- Simulated AI community coach
- Help, safeguards, and QA/testing steps

## State rules
- Newly joined: joined 0–5 days ago
- Dormant: no activity in the last 30 days OR last activity 21+ days ago
- At risk: last activity 10–20 days ago
- Highly active: 6+ activities in the last 30 days
- Active: remaining members with recent activity

## AI safeguard
The AI coach is explicitly simulated. It uses only recorded CRM activity and profile fields, makes no outbound communication, does not invent personalisation, and does not score buying intent. A human must review any suggested next step.

## Run
Open `index.html` in a browser. For a local server:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

For the assignment, publish the folder to a static host such as GitHub Pages, Netlify, or Vercel and submit the public URL. The ZIP itself is not the required live submission.
