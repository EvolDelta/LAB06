# LAB 6 — Answers

1. In one sentence: What does `res.render(view, data)` do?

Renders the specified view template using the configured view engine with the provided data and sends the resulting HTML to the client.

2. What is the difference between `<%= %>` and `<%- %>`?

`<%= %>` outputs escaped HTML (safe for display), whereas `<%- %>` outputs unescaped/raw HTML (use carefully).

3. Where does Express look for EJS templates (folder path)?

By default Express looks in the `views` folder; in this project it's set to `path.join(__dirname, '..', 'views')` (the project's `views/` directory).
