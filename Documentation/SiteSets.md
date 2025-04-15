# Rename Site Sets -> Configuration Sets

* **Status:** Proposed 
* **Target Version:** TYPO3 14.0

## Rationale

- **"Site Sets" is misleading**: It suggests the config is tied only to site packages,
  but sets can be used by *any* extension, and don’t include templates or content.
- **"Configuration Sets" is explicit**: Clearly indicates that these are reusable
  groups of configuration files like TypoScript, TSconfig, or YAML settings.
- **Improves developer clarity**: Makes the scope and purpose of the feature
  easier to understand for developers and integrators.
- **Aligns with modern ecosystems**: Similar terminology is used in Drupal
  (Config Set), Symfony (Config Pack), and Laravel (Config files).
- **Future-proof**: Name remains valid even as the concept grows beyond site-only use.

## Evaluation

| Criterion       | Meets? | Notes                                                              |
|----------------|--------|--------------------------------------------------------------------|
| Unique         | ✅     | Not used elsewhere in TYPO3 UI; avoids confusion with site config. |
| Clear          | ✅     | Clearly indicates this is a group of configuration files.           |
| Self-evident   | ✅     | Developers understand its intent from the name alone.               |
| Familiar       | ✅     | Matches patterns from other systems like Drupal and Symfony.        |
| Plain          | ✅     | Simple, descriptive, no jargon.                                     |
| English        | ✅     | Correct American English, easy to read and document.                |

## Affected Areas

- UI Labels
- Documentation


## Supporters

- Lina Wolf (Documentation, native German speaker)
