---
title: Author attribution
authors:
  - Jan Kowalski
  - john-doe
  - John Doe
---

This page has the following in the frontmatter:
```
authors:
  - Jan Kowalski
  - john-doe
  - John Doe
```

`Jan Kowalski` doesn't have a corresponding profile page in the repo at all, so his name should just be displayed as plain text.

`john-doe` should match `/team/john-doe.md` based on file name and:
- his full name - `John Doe` - should be displayed (as set by the `title` frontmatter field)
- it should link to his profile page.

`John Doe` should also match `/team/john-doe.md` based on `title` frontmatter field, and should also link to his profile page.
