Version 9 of Highlight.js has reached EOL and is no longer supported.
Please upgrade or ask whatever dependency you are using to upgrade.
https://github.com/highlightjs/highlight.js/issues/2877

Version 9 of Highlight.js has reached EOL and is no longer supported.
Please upgrade or ask whatever dependency you are using to upgrade.
https://github.com/highlightjs/highlight.js/issues/2877

## v3.0.0-beta.6 (2021-01-25)

#### :rocket: Enhancement
* [#701](https://github.com/adopted-ember-addons/ember-electron/pull/701) Make embroider-compatible ([@bendemboski](https://github.com/bendemboski))

#### :memo: Documentation
* [#700](https://github.com/adopted-ember-addons/ember-electron/pull/700) Change `vendor.js` to `app.js` in documentation ([@bendemboski](https://github.com/bendemboski))

#### :house: Internal
* [#704](https://github.com/adopted-ember-addons/ember-electron/pull/704) Build on MacOS in CI ([@bendemboski](https://github.com/bendemboski))
* [#702](https://github.com/adopted-ember-addons/ember-electron/pull/702) Parallelize end-to-end tests ([@bendemboski](https://github.com/bendemboski))
* [#698](https://github.com/adopted-ember-addons/ember-electron/pull/698) Update Ember to 3.24 ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 3
- Ben Demboski ([@bendemboski](https://github.com/bendemboski))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.0.0-beta.5 (2021-01-22)

#### :rocket: Enhancement
* [#685](https://github.com/adopted-ember-addons/ember-electron/pull/685) fix: replace deprecated 'crashed' event ([@knownasilya](https://github.com/knownasilya))
* [#676](https://github.com/adopted-ember-addons/ember-electron/pull/676) Set `contextIsolation` to false for tests ([@rwwagner90](https://github.com/rwwagner90))
* [#638](https://github.com/adopted-ember-addons/ember-electron/pull/638) Fix making/building with a custom output path ([@bendemboski](https://github.com/bendemboski))

#### :memo: Documentation
* [#668](https://github.com/adopted-ember-addons/ember-electron/pull/668) Mention `nodeIntegration` in the documentation ([@bendemboski](https://github.com/bendemboski))
* [#646](https://github.com/adopted-ember-addons/ember-electron/pull/646) fix: typo in link to github profile page of author ([@jl-cs](https://github.com/jl-cs))

#### :house: Internal
* [#699](https://github.com/adopted-ember-addons/ember-electron/pull/699) Remove Mac from tests ([@rwwagner90](https://github.com/rwwagner90))
* [#697](https://github.com/adopted-ember-addons/ember-electron/pull/697) Run Windows and MacOS tests with GH Actions ([@rwwagner90](https://github.com/rwwagner90))
* [#695](https://github.com/adopted-ember-addons/ember-electron/pull/695) Move inline scripts to public folder, document CSP setup ([@rwwagner90](https://github.com/rwwagner90))
* [#671](https://github.com/adopted-ember-addons/ember-electron/pull/671) Convert to GitHub actions ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 5
- Ben Demboski ([@bendemboski](https://github.com/bendemboski))
- Ilya Radchenko ([@knownasilya](https://github.com/knownasilya))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)
- [@jl-cs](https://github.com/jl-cs)

## v3.0.0-beta.4 (2020-09-16)

#### :bug: Bug Fix
* [#589](https://github.com/adopted-ember-addons/ember-electron/pull/589) Fix handle-file-urls on Windows ([@bendemboski](https://github.com/bendemboski))

#### :memo: Documentation
* [#576](https://github.com/adopted-ember-addons/ember-electron/pull/576) Add IndexedDB migration instructions ([@rwwagner90](https://github.com/rwwagner90))
* [#490](https://github.com/adopted-ember-addons/ember-electron/pull/490) Correct the link to felixs github ([@spruce](https://github.com/spruce))

#### Committers: 4
- Ben Demboski ([@bendemboski](https://github.com/bendemboski))
- Felix Fichte ([@spruce](https://github.com/spruce))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.0.0-beta.3 (2020-05-22)

#### :boom: Breaking Change
* [#476](https://github.com/adopted-ember-addons/ember-electron/pull/476) Switch from electron-protocol-serve to file: URLs ([@bendemboski](https://github.com/bendemboski))

#### :rocket: Enhancement
* [#465](https://github.com/adopted-ember-addons/ember-electron/pull/465) Install devtron from the main process ([@rwwagner90](https://github.com/rwwagner90))
* [#458](https://github.com/adopted-ember-addons/ember-electron/pull/458) Install inspector via electron-devtools-installer ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 2
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.0.0-beta.2 (2020-04-28)

#### :boom: Breaking Change
* [#446](https://github.com/adopted-ember-addons/ember-electron/pull/446) Drop node 8 support ([@rwwagner90](https://github.com/rwwagner90))

#### :memo: Documentation
* [#439](https://github.com/adopted-ember-addons/ember-electron/pull/439) Fix Docs URL ([@devotox](https://github.com/devotox))

#### Committers: 2
- Devonte ([@devotox](https://github.com/devotox))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v3.0.0-beta.1 (2019-12-22)

#### :rocket: Enhancement
* [#437](https://github.com/adopted-ember-addons/ember-electron/pull/437) Update to electron-forge beta 47 ([@bendemboski](https://github.com/bendemboski))
* [#433](https://github.com/adopted-ember-addons/ember-electron/pull/433) feat: check dependencies in Electron project ([@bendemboski](https://github.com/bendemboski))

#### :bug: Bug Fix
* [#434](https://github.com/adopted-ember-addons/ember-electron/pull/434) fix: update .travis.yml correctly from the blueprint ([@bendemboski](https://github.com/bendemboski))
* [#438](https://github.com/adopted-ember-addons/ember-electron/pull/438) fix: update docs root URL ([@bendemboski](https://github.com/bendemboski))
* [#432](https://github.com/adopted-ember-addons/ember-electron/pull/432) fix: use a single version of electron-forge ([@bendemboski](https://github.com/bendemboski))
* [#424](https://github.com/adopted-ember-addons/ember-electron/pull/424) fix: install devtron and ember-inspector ([@bendemboski](https://github.com/bendemboski))

#### :memo: Documentation
* [#436](https://github.com/adopted-ember-addons/ember-electron/pull/436) Update docs URL ([@bendemboski](https://github.com/bendemboski))
* [#421](https://github.com/adopted-ember-addons/ember-electron/pull/421) Docs after release ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 2
- Ben Demboski ([@bendemboski](https://github.com/bendemboski))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v3.0.0-beta.0 (2019-11-25)

#### :boom: Breaking Change
* [#418](https://github.com/adopted-ember-addons/ember-electron/pull/418) Update to electron-forge 6 & simplify build pipeline/project structure ([@bendemboski](https://github.com/bendemboski))

#### :rocket: Enhancement
* [#412](https://github.com/adopted-ember-addons/ember-electron/pull/412) chore: Fix vendor weirdness ([@bendemboski](https://github.com/bendemboski))

#### :memo: Documentation
* [#414](https://github.com/adopted-ember-addons/ember-electron/pull/414) docs: Link to docs in README ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#417](https://github.com/adopted-ember-addons/ember-electron/pull/417) chore: Update Appveyor badge link ([@rwwagner90](https://github.com/rwwagner90))
* [#415](https://github.com/adopted-ember-addons/ember-electron/pull/415) chore: Speed up travis build ([@bendemboski](https://github.com/bendemboski))

#### Committers: 2
- Ben Demboski ([@bendemboski](https://github.com/bendemboski))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))


## v2.10.2 (2019-11-16)

#### :memo: Documentation
* [#405](https://github.com/adopted-ember-addons/ember-electron/pull/405) docs: Change links to docs, port index page ([@rwwagner90](https://github.com/rwwagner90))
* [#404](https://github.com/adopted-ember-addons/ember-electron/pull/404) docs: Use ember-cli-addon-docs for docs ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#413](https://github.com/adopted-ember-addons/ember-electron/pull/413) fix: Disable fingerprinting on images ([@rwwagner90](https://github.com/rwwagner90))
* [#410](https://github.com/adopted-ember-addons/ember-electron/pull/410) chore: Make ESLint config more standard ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 1
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

