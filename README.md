# A11y Workshop

This repository contains tasks for the accessibility workshop.

## Getting started

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run serve
```

## General information

This is the result of a workshop held 29.09.2020  
The solution is a work in progress  
The original task is here: https://github.com/tajakobsen/a11y-workshop  
Tools: Chrome Developer Tools/Lighthouse, Wave plugin, ChromeVox, VoiceOver (MAC)

## Observations

You need a way to reload the browser cache. Loading it with DevTools open and "Disable cache" works.  
Lighthouse and Wave plugin seems to work well for the page after loading, but it does not seem like they can discover accessibility issues after the user has interacted with the page.  

## Task 1

- Made background slightly darker for better contrast
- Added alt to images
- Added roles to tablist and tabs
- Now uses the role attribute in selectors. Classes with the same names as the roles have been removed.
- Completed the other ARIA-instructions. Works with VoiceOver, but there seems to be problems with ChromeVox.

## Task 2

- TODO: Look at this task.
