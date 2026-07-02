# Learn With PMK71

Learn QA Software Testing with PMK — Prashanth M K

## Structure

```
learn-with-pmk71/
├── index.html              ← homepage (the cards/links page)
├── guides/
│   ├── typescript-playwright-guide.html   ← first guide
│   └── api-testing-guide.html             ← API testing guide
└── README.md
```

## Adding a new guide

1. Drop your new guide `.html` file into `guides/`
2. Open `index.html`, find the `<!-- TEMPLATE -->` comment block inside the `.grid` section
3. Copy that commented block, uncomment it, and update:
   - `href` → path to your new file in `guides/`
   - emoji icon, title, description, tags
4. Save and refresh — done.
