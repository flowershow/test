---
datapackage:
  licenses:
  - name: license-1
    path: "https://licence-1.com"
    title: License 1 Title
  resources:
  - encoding: utf-8
    format: csv
    name: resource-1
    path: data/resource-1.csv
    profile: tabular-data-resource
    schema:
      fields:
      - format: "%Y-%m-%d"
        name: Date
        type: date
      - decimalChar: "."
        format: default
        groupChar: ''
        name: Price
        type: number
  - encoding: utf-8
    format: csv
    name: resource-2
    path: data/resource-2.csv
    profile: tabular-data-resource
    schema:
      fields:
      - format: "%Y-%m-%d"
        name: Date
        type: date
      - decimalChar: "."
        format: default
        groupChar: ''
        name: Price
        type: number
  - encoding: utf-8
    format: csv
    name: resource-3
    path: https://external-data.org/resource-3.csv
    profile: tabular-data-resource
    schema:
      fields:
      - format: "%Y-%m-%d"
        name: Date
        type: date
      - decimalChar: "."
        format: default
        groupChar: ''
        name: Price
        type: number
  sources:
  - name: source-1
    path: "https://source-1.com"
    title: Source 1 Title
  - name: source-2
    path: "https://source-2.com"
    title: Source 2 Title
  views:
  - name: view-1
    resourceName: resource-1
    spec:
      group: Date
      series:
      - Price
      type: line
    specType: simple
    title: View 1 Title
---

# Datapackage with frontmatter title

Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description Datapackage with frontmatter description
