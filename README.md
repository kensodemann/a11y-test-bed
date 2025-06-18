# A11yTestBed

The intent here is to wrap a non-Ionic application in Capacitor so we can test out how standard HTML elements behave with regard to TalkBack and VoiceOver. This is meant to be functional for testing, and not meant to be pretty. In many cases, it is also showing bad coding patterns just to drive home the fact that certain patterns that people try to implement should not be used.

AAMOF, in many cases bad practices are followed simply to show how annoying the results actually are.

The secondary intent is to show that TalkBack and VoiceOver behave differently and that is just life. **Do NOT** expect the same results on each OS.

This app is intended to be run on native devices with the proper assistive tech enabled.

- `npm i`
- `npm run build`
- `npx cap open android`
- `npx cap open ios`

## Potentially Useful Docs

- [Using ARIA](https://www.w3.org/TR/using-aria/): This is a very practical guide. Read this first, and understand the rules.
- [Providing Accessible Names and Descriptions](https://www.w3.org/WAI/ARIA/apg/practices/names-and-descriptions/): TL;DR version is "properly use labels, for the most part, fill in with other stuff _only_ when needed." Good reading and most people have issues in this area. Pay attention to the warnings.
- [Cardinal Rules of Naming](https://www.w3.org/WAI/ARIA/apg/practices/names-and-descriptions/#cardinalrulesofnaming): Naming is hard, but these are very good rules, especially Rule 2. _Always_ follow rule 2.
- [Composing Effective and User-friendly Accessible Names](https://www.w3.org/WAI/ARIA/apg/practices/names-and-descriptions/#naming_effectively): Again, naming is hard, but these guides help you to create good names that don't annoy your users.


