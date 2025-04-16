# 📁 Rename Sys Folder -> Data Folder

* **Status:** Proposed
* **Target Version:** TYPO3 14.0

## Rationale

- **"Sys Folder" is technical and unclear**, especially for editors. The term
  originates from TYPO3's internal naming conventions and suggests a system-level
  folder rather than a place for storing reusable or structured data.
- The folder is **commonly used for storing data records**, such as users,
  categories, forms, or content elements not directly shown on the website.
- **"Data Folder" is more intuitive and descriptive**: it indicates the folder
  contains structured or reusable data rather than pages.
- This change improves **editor understanding and onboarding**, especially for
  those unfamiliar with TYPO3's historical terminology.
- Aligns better with terminology used in other CMSs, where similar structures are
  often labeled as "Data", "Content Models", or "Collections".

## Evaluation

| Criterion       | Meets? | Notes                                                                     |
|----------------|--------|---------------------------------------------------------------------------|
| Unique         | ✅     | "Data Folder" is not used elsewhere in the UI with a conflicting meaning. |
| Clear          | ✅     | Suggests a folder that holds structured or reusable content/data.         |
| Self-evident   | ✅     | Editors can infer the purpose without documentation.                      |
| Familiar       | ✅     | Similar to terms used in other cms                                        |
| Plain          | ✅     | Non-technical, easy to understand.                                        |
| English        | ✅     | Proper English; more user-friendly than "Sys".                            |


## Affected Areas

- UI labels (e.g., in the page tree, "Create new Sys Folder")
- Documentation and tutorials

## Supporters

- Lina Wolf (Documentation, native German speaker)