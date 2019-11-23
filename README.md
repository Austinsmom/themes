# Windows Terminal Themes

Preview and copy themes for the new Windows Terminal (Preview).

[Visit site at https://atomcorp.github.io/themes/](https://atomcorp.github.io/themes/)

---

### Info

All the themes are copied from [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes). So thanks and credit to them and all the theme designers.

The json list of themes `public/colour-schemes.json` is generated by running `yarn themes`.

Install and test using `yarn start` and `yarn test`, respectively.

To use, open up Windows Terminal settings (a file called `profile.json` will open), copy a theme from this site into the `schemes` section and then reference the name your chosen profile in the `profiles` section.

### Notes

- fun stuff being used: React (CRA), TypeScript, Jest, Node (for getting themes), testing-library, Githun Pages and CSS Grid
- thanks [clipboard-polyfill](https://github.com/lgarron/clipboard-polyfill), [resize-observer-polyfill](https://github.com/que-etc/resize-observer-polyfill) and [get-contrast](https://github.com/johno/get-contrast)