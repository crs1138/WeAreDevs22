## Users

- visual impairment
- low hearing
- motor imp
- cognitive imp (migrains) - avoid flashing content or warn ahead

## "Us" vs "Them"

We often think about implementing a11y on top of our code. We all are gonna get old and we are likely to relly on a11y of some sort at some point in our life.

## Guidelines - WCAG

13 guidelines in 4 groups:

- perceivable (in thew way the user can)
- operable (in thew way the user can)
- understandable (in thew way the user can)
- robust

Every guideline has different levels:

- A basic a11y features (must be implemented)
- AA worldwide legal standard (list of laws)
- AAA extended a11y features 

https://www.w3.org./WAI/WCAG21/quickref

## Testing for A11y

Starting with a checklist:

- [x] Define your most important use cases (we want the user to ...)
- [ ] Monitor from begining
- [ ] Or begin optimizing from the most important use case

a11yproject.org/checklist

### a11y audits dev tools

- Chrome Lighthouse => accessibility
- Firefox Dev Tools => Accessibility => Check for issues
- [Wave](https://wave.webaim.org)
- aXe Core
  - CLI
  - pure JS API
  - Wrapper
  - used in Lighthouse
- pa11y
  - CLI
  - pure JS
  - wrappers
  - dashboard App

## Manual Screen Reader Testing

- Windows: NVDA
- Mac: VoiceOver
- Linux:
  - Orca
  - [BRKTTY](https://brltty.app)
  - Voxin


## Color
## Keyboard
