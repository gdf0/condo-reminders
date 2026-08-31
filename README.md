# Condo Maintenance — Admin Page (public)

This public repo only hosts the password-protected admin page via GitHub
Pages. All data (tasks, credentials, recipients) lives in the private
`condo-reminders-private` repo — this page reads/writes it through the GitHub API
after you sign in with the admin password.

- `config.js` is generated with `setup.html`; the GitHub token inside it
  is AES-256 encrypted with the admin password and is safe to publish.
- Enable Pages: Settings → Pages → Deploy from branch `main`, root folder.
