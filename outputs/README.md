# ProfilePilot website

A responsive localhost website prototype for managing job profile updates and comparing resume text against a master profile.

## Start

From this directory, run:

```sh
npm start
```

Then open <http://localhost:4173>.

## Included flows

- Overview for LinkedIn and Naukri, update task counts, and upcoming tasks.
- Add tasks for both profiles; mark tasks complete or filter the list.
- Edit a master target role and comma-separated skills.
- Select a PDF/Word resume, paste its text, and identify target-role or skill mismatches.
- Turn mismatch findings into LinkedIn and Naukri review tasks.

The chosen resume remains in the browser and its text is not extracted or sent to a server. Paste the resume text to compare it. Account connections and profile scores are illustrative; the site does not sign into or read/write live LinkedIn or Naukri profiles. The local server serves static files only.
