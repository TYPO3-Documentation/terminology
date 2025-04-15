# TYPO3 Terminology Updates

This document serves as a living reference for terminology changes in TYPO3. It aims to improve clarity, consistency,
and inclusiveness across the system and documentation. Inspired by Agility CMS's approach to terminology modernization.

:Repository:  https://github.com/TYPO3-Documentation/terminology
:Read online: https://docs.typo3.org/m/typo3/terminology/main/en-us/Index.html

## Contribute

You can contribute by using the "Edit on GitHub" workflow or by cloning the repository with 

```
git clone git@github.com:TYPO3-Documentation/terminology.git
```

Then fork the repository and add your own fork as remote:

```
git remote add myfork git@github.com:yourusername/terminology.git
```

Create a new terminology proposal by copying the template:

```
cp Documentation/TerminologyProposalTemplate.md.txt Documentation/YourTermToBeChanged.md
```

Then open Documentation/YourTermToBeChanged.md in your editor and update the content to describe your proposed terminology change.

Once done, commit your changes:

```
git checkout -b my-terminology-update
git add Documentation/YourTermToBeChanged.md
git commit -m "Add proposal to replace 'YourTermToBeChanged' with 'NewPreferredTerm'"
```

Push to your fork:
```
git push myfork my-terminology-update
```
Then open a Pull Request at:
https://github.com/TYPO3-Documentation/terminology/pulls

You can try out your changes with the following command:

```
make docs
```
