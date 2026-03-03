Purpose of Each Workflow

Workflow 1 – Dependent Jobs
Demonstrates sequential job execution using "needs".  
The jobs run in order: build → test → deploy.

Workflow 2 – Multi-Platform Testing
Demonstrates parallel execution across different operating systems (Ubuntu, Windows, macOS).

---

Key Concepts Demonstrated

- "needs": Creates job dependencies (sequential execution).
- "runs-on": Specifies which OS runner executes the job.
- "env": Defines environment variables used inside jobs.

---

Challenges Faced & Resolutions

- Different OS commands (Linux uses "cat", Windows uses "type").
  → Used OS-specific commands.
- YAML indentation errors.
  → Corrected formatting and checked GitHub Actions logs.
