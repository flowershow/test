---
title: Author attribution
authors:
  - Jan Kowalski
  - john-doe
  - Jane Doe
---

This page has the following in the frontmatter:
```
authors:
  - Jan Kowalski
  - john-doe
  - Jane Doe
```

`Jan Kowalski` doesn't have a corresponding profile page in the repo at all, so his name should just be displayed as plain text.

`john-doe` should match `/team/john-doe.md` based on file name and:
- his full name - `John Doe` - should be displayed (as set by the `title` frontmatter field)
- it should link to his profile page.

`Jane Doe` should  match `/team/jane-doe.md` based on the `title` frontmatter field, and should also link to the profile page.
