
# 📁 Rename Filelist -> Media

* **Status:** Under Review  
* **Target Version:** TYPO3 v14.0  
* **Forge Issue:** [#106471](https://forge.typo3.org/issues/106471)  
* **Gerrit Change** [#89079](https://review.typo3.org/c/Packages/TYPO3.CMS/+/89079)
* **Tags:** `ux-decision`, `terminology`

## Rationale

- "Filelist" is not a familiar term for most users, especially non-German speakers. It carries a "Denglish" tone.
- The module is specifically about managing **media and downloadable content**, not general files.
- “Media” is a widely accepted and intuitive term across other CMS platforms (e.g., WordPress, Drupal).
- Improves **usability** and **discoverability** for new users.

## Evaluation

| Criterion       | Meets? | Notes                                    |
|----------------|--------|------------------------------------------|
| Unique         | ✅     | No other module uses “Media”             |
| Clear          | ✅     | Accurately describes the module’s role   |
| Self-evident   | ✅     | Tells users what to expect                |
| Familiar       | ✅     | Standard in CMSs                         |
| Plain          | ✅     | Simple, short, and widely understood     |
| English        | ✅     | American English, no localization issues |

## Affected Areas

- Module label and icon
- Navigation/backend menu
- Help texts, inline docs
- User documentation, manuals
- Translation files
- Screenshots and UI visuals
- name of EXT:filelist

## Supporters

- Rachel Foucard (UX, native French speaker)
- Lina Wolf (Documentation, native German Speaker)
- Sarah McCarthy (Documentation, native English speaker)
- Mathias Bolt Lesniak (Documentation, native Norwegian speaker)
- Benni Mack (Core, native German Speaker)
