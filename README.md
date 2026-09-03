# My Daily To-Do App

A fully featured, self-contained daily task manager that runs directly in any web browser — no installation, no backend, no dependencies.

## Features

- **⭐ Today view** — see all tasks due today or overdue across every list
- **🔁 Recurring tasks** — daily, weekly, or monthly repeats
- **📌 Multiple lists** — Personal, Work, or any custom list with color labels
- **🎯 Priority levels** — High, Medium, Low with color-coded indicators
- **📅 Due dates & reminders** — browser notifications when a reminder fires
- **🔍 Search, filter & sort** — by priority, category, due date, or A–Z
- **☰ Subtasks** — break any task into smaller steps with a progress bar
- **🧹 Clear Done** — remove completed tasks in one click
- **🌙 Dark mode** — toggle light/dark theme
- **⬆⬇ Import/Export** — backup as JSON or export to CSV
- **N shortcut** — press `N` anywhere to jump to the add-task input
- **💾 Auto-save** — all data persists in browser localStorage

## Usage

Just open `index.html` in any modern browser. No server needed.

```
double-click index.html
```

Or serve it locally:
```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`

## Project Structure

```
todo-app/
├── index.html      # Everything: HTML + CSS + JS in one file
└── README.md
```

## Roadmap

- [ ] Backend API integration (Node.js / Express)
- [ ] User authentication
- [ ] Cloud sync across devices
- [ ] Mobile app (PWA)
- [ ] Calendar view
- [ ] Shared / collaborative lists

## Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "feat: add my feature"`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

## License

MIT
