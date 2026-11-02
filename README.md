# The 2 AM Page

An interactive incident response tabletop. You're on call when an incident begins. You make the decisions a response team has to make, from the first hour through notification and the review a month later, and see how each one plays out.

**Play it:** https://jckesler.github.io/the-2am-page/

It takes about 15 minutes. There's no login, nothing to install, and no timer.

## The scenarios

Each play picks one of three companies at random, or you can choose one.

| Scenario | Company | What it's about |
|---|---|---|
| **Harbor Ridge Health** | Regional health system, Norfolk, Virginia | Ransomware through a remote-access portal without MFA, HIPAA breach notification, and keeping hospitals running |
| **Pinecrest Outfitters** | Publicly traded outdoor retailer, Asheville, North Carolina | Help-desk social engineering, an extortion demand, SEC Form 8-K disclosure, and North Carolina's breach law |
| **Larkspur HR** | HR and benefits software vendor, Denver, Colorado | Stolen integration tokens at a vendor that holds other companies' data, and what a processor owes its customers |

The companies are invented. Each scenario is modeled on publicly reported incidents:

- **Harbor Ridge Health:** Change Healthcare (2024), and a 2017 ransomware attack on a regional US health system that neighboring health systems helped it recover from.
- **Pinecrest Outfitters:** MGM Resorts and Caesars Entertainment (2023).
- **Larkspur HR:** the Salesloft Drift OAuth token theft (2025).

The debrief at the end of each scenario describes what actually happened in those incidents.

## How it works

- Each scene gives you a situation and two to four choices. The order of the choices is shuffled every time, so the letter tells you nothing.
- Your choices move three meters: business disruption, legal exposure and customer trust.
- Every decision is written to a decision log, timestamped as it would be in a real response.
- Each choice is rated as a strong call, partly right, or a costly call, with a short explanation and the incident response topic behind it.
- At the end, a debrief walks through every decision you made.

## Ways to use it

- **On your own.** Play a scenario, then replay it and try different choices.
- **In a group.** Put it on a screen and have the group debate each decision before anyone clicks. This is where it works best as a tabletop: the arguments about who makes the call, and when, are the point.
- **In a class or workshop.** Link to the page, or download `index.html` and upload it to a learning management system. It's a single self-contained file.

## Accuracy

The legal and regulatory details (HIPAA, SEC Form 8-K, GDPR, and the Virginia and North Carolina breach laws) were checked against primary sources in November 2026. They're simplified to fit a game, and laws change. Nothing here is legal advice. In a real incident, your counsel decides what applies.

## Technical notes

- One HTML file with plain JavaScript. There are no frameworks and no build step.
- Nothing is stored or sent anywhere. The game keeps no cookies or local storage and has no analytics.
- The only external request is for fonts from Google Fonts. Offline, the page falls back to system fonts and still works.
- It works on phones as well as desktops, and supports light and dark mode.

## License

© 2026 Chuck Kesler. Licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). See [LICENSE](LICENSE).

You're welcome to use and adapt it for teaching, training and other non-commercial purposes, with credit. For commercial use, please get in touch.

## About

Written by [Chuck Kesler](https://www.linkedin.com/in/chuckkesler/), a CISO who teaches data security and privacy at NC State University's Poole College of Management. It began as an optional activity for his graduate course.
