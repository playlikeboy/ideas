# Adding an Idea

## 1. Choose a category

Use:
- `startup/` for venture/startup concepts
- `projects/` for technical or product projects
- `libs/` for reusable developer libraries/tools

## 2. Copy the correct template

- Startup: [templates/startup.md](../templates/startup.md)
- Project: [templates/project.md](../templates/project.md)
- Library: [templates/lib.md](../templates/lib.md)

## 3. Create a dedicated folder

Prefer:

```
startup/<slug>/README.md
startup/<slug>/CONTACTS.md
startup/<slug>/VALIDATION.md
startup/<slug>/ROADMAP.md
```

Not every idea needs every file immediately. Start small and expand as the idea becomes serious.

## 4. Add the contact record

Create:

```
contacts/<slug>.md
```

Only use intentionally public contact information.

## 5. Update the catalog

Add the idea to [IDEA-CATALOG.md](./IDEA-CATALOG.md).

## 6. Keep the web dashboard compatible

The existing dashboard reads Markdown frontmatter from the repository. Keep frontmatter valid and use the established category/folder structure.

## 7. Publish

Push to `main`. The repository's GitHub Actions Pages workflow publishes the site automatically.
