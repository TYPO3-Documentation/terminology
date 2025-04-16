# Rename Backend Layout -> Page Template

* **Status:** Proposed
* **Target Version:** TYPO3 14.0

## Rationale

- **"Backend Layout" is misleading**: It suggests the setting only affects the
  backend view, but it also controls the frontend template, especially with the
  `pageview` TypoScript object.

- **"Page Template" is clearer and modern**: It reflects both the backend
  layout structure and the frontend rendering logic.

- **Improves usability**: Editors can better understand that they are selecting how
  a page is structured and displayed, not just its backend grid layout.

- **Aligns with common CMS terminology**: Other CMSs like WordPress and Drupal
  use "Page Template" for similar functionality, reducing confusion for new
  users.

- **Supports TYPO3's architectural direction**: TYPO3 is moving toward more
  template-driven configuration, and this rename better reflects that evolution.

## Evaluation

| Criterion       | Meets? | Notes                                                              |
|----------------|--------|--------------------------------------------------------------------|
| Unique         | ✅     | Not used elsewhere in TYPO3 in a conflicting way.                  |
| Clear          | ✅     | Clearly indicates its role in selecting a layout/template.         |
| Self-evident   | ✅     | Users can infer it controls how the page is rendered.              |
| Familiar       | ✅     | Used in other CMSs like WordPress, Drupal, and Joomla.             |
| Plain          | ✅     | Simple, straightforward language without jargon.                   |
| English        | ✅     | Correct American English, no translation or technical compound.    |

##  Other CMS

### WordPress "Page Templates"

- **Usage**: Page templates define how individual pages are displayed.
- **UI Location**: In the editor under *Page Attributes → Template*, users can
  select a *Page Template*.
- **Documentation**: https://developer.wordpress.org/themes/template-files-section/page-template-files/
  
### Drupal

- **Usage**: Drupal’s theme system uses template files like
  ``page--[type].html.twig`` to control page rendering.
- **Terminology**: While template selection is more implicit, the concept of a
  *Page Template* is referred to in documentation and theme development.
- **Documentation**: https://www.drupal.org/project/pate


## Affected Areas

- UI label
- Documentatopm
- Page TSconfig
- database field (?)


## Supporters

- Lina Wolf (Documentation, native German speaker)
