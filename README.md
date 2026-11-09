# youbot-stack — Robot Programming 2026/27

Mobile manipulation stack for the KUKA youBot. Exam goal: the robot autonomously moves between three tables and sorts colored cubes by color.

## Rules

- One monorepo, 22 teams, each team owns one component for the whole course.
- `main` only through PR; one `feature/*` branch per ticket.
- A team changes only its own packages `src/<track>/<component>`; contracts live in the shared `interfaces` package and change only with lecturer approval.
- Contract and mock first: interface PR + mock before any consumer work.
- Definition of Done, frozen contracts, component table: course docs (`docs/course.md`, `docs/backlog.md` in the course repo).

## Layout

- `interfaces/` — shared message/service/action definitions (lecturer-approved)
- `src/<track>/<component>/` — team-owned packages
- `docs/adr/` — architecture decision records, written in class before code

## Teams

Team → component mapping and responsibility chains: `TEAMS.md`.
