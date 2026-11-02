# Orbit

**A space-themed progress tracker and weekly planner. Your projects are planets, sub-projects are moons, tasks are glowing stars — with a due-date timeline on top and a weekly planner that stays in sync.**

Two plain HTML files. No install, no server, no account. Your data stays in your browser.



![Home view](assets/home.png)

## Try it

Open `index.html` in your browser — that's it. Keep `index.html` and `weekly-planner.html` in the same folder so the **Week ↗** button works. On first launch you get a short welcome and a small example to play with (or start fresh).

Want it online? Enable **GitHub Pages** (Settings → Pages → *Deploy from a branch* → `main` / root) and it is served at `https://<your-username>.github.io/<repo-name>/`.

## What you can do

| | |
|---|---|
| **Planets = projects** | Name them, pick a colour, set progress — the liquid level shows how far along you are. |
| **Closer = more done** | The further along a project is, the closer it orbits the sun. |
| **Fly in** | Click a planet to open its own page and add sub-projects (they orbit as moons). Click the sun or press `Esc` to fly back. |
| **Drag to edit** | Drag a planet onto the black hole to open its edit panel: notes, link, to-dos, progress, colour. |
| **Drag to nest** | Drag a planet onto another planet to make it a sub-project. |
| **Tasks as stars** | **★ Make task** turns a bubble into a small glowing star. Hover to read it. |
| **To-dos + due dates** | Every bubble has a to-do list. Items show as stars in the orbit and on the timeline. |
| **Timeline** | Always visible at the top, scoped to the page you're on. Zoom with **Week / Month / 3 mo / All**. |
| **Merge** | **⛓ Merge** links a bubble to another one, so the same thing can live in two places. |
| **Times = events** | Give a to-do a time and it becomes an event, shown with its time on the timeline. |
| **Obsidian links** | A bubble's link can point to a note: type `[[My note]]` (Orbit asks for your vault name once). |
| **Palettes** | 16 colour palettes, shared with the weekly planner. |
| **Week ↗** | Opens the weekly planner (see below). |
| **Home is yours** | Double-click the sun to rename it — use it for projects, hobbies, gifts, birthdays, anything. |

![A project page](assets/project.png)

## Weekly planner

![Weekly planner](assets/week.png)

`weekly-planner.html` is a separate page, opened with the **Week ↗** button (and **← Orbit** takes you back).

| | |
|---|---|
| **Every task lives in Orbit** | Adding a task asks which bubble it belongs to. Ticking, renaming, dates and times stay in sync both ways, and the **from Orbit ↗** tag jumps to where it lives. |
| **Plan the week** | Drag tasks from the backlog onto days. Putting a task on a day also sets its due date, so it shows on the Orbit timeline. |
| **Focus blocks** | Each day has a number of 50-minute focus blocks. A ring shows how full the day is. |
| **Events and fixed commitments** | **+ Event** adds a one-off event with a time. **Setup** holds repeating commitments (lectures, labs…) and weekly routines. |
| **Auto-arrange** | **Plan my week** picks tasks and spreads them over the free blocks, overdue and due-soon first, keeping Sunday light. |
| **Palettes** | **Same as Orbit**, or any of the 16 palettes. |

The planner reads your Orbit data from the same browser, so open both pages from the same place.

## Saving your data

- Changes are saved **automatically in your browser** (localStorage).
- **Link file** (Chrome, Edge, Brave): pick a JSON file once and Orbit autosaves to it from then on — handy for keeping it in a synced folder.
- **Save / Load**: download or restore a JSON backup, in any browser.

The planner has its own **Link file** / **Save** / **Load** too. Browser storage is per browser and per file location, so use **Link file** or **Save** if you want a safety net.

## Tech

Plain HTML, CSS and JavaScript — no dependencies, no build step. Orbit lives in `index.html`, the planner in `weekly-planner.html`.

## License

MIT — © 2026 Elena Teissier. See [LICENSE](LICENSE).

## Contributors

- Elena Teissier
- - Claude (Anthropic)
  - 
