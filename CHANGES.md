## 1.2.0 (202?-??-??)

- Vue3... https://github.com/tupilabs/vue-lumino/issues/51...
- Bump webpack from 5.64.4 to 5.76.0 #52
- Bump semver from 5.7.1 to 5.7.2 #54
- Bump word-wrap from 1.2.3 to 1.2.4 #55
- Bump @babel/traverse from 7.10.4 to 7.23.2 #56
- Upgraded versions of GitHub Actions used, added Node setting it to v14 (due to SSL issues with 18+)
- Bump browserify-sign from 4.2.0 to 4.2.2 #57

## 1.1.5 (2023-03-11)

- Bump follow-redirects from 1.12.1 to 1.14.7 #38
- Bump cached-path-relative from 1.0.2 to 1.1.0 #39
- Bump follow-redirects from 1.14.7 to 1.14.8 #40
- Bump url-parse from 1.5.3 to 1.5.7 #42
- Bump url-parse from 1.5.7 to 1.5.10 #43
- Bump eventsource from 1.0.7 to 1.1.1 #44
- Bump shell-quote from 1.7.2 to 1.7.3 #45
- Bump terser from 4.8.0 to 4.8.1 #46
- Bump decode-uri-component from 0.2.0 to 0.2.2 #47
- Bump minimatch from 3.0.4 to 3.1.2 #48
- Bump express from 4.17.1 to 4.18.2 #50
- Bump qs from 6.5.2 to 6.5.3 #49
- Bump ajv from 6.12.2 to 6.12.6 #41

## 1.1.4 (2021-12-06)

- Bump ws from 5.2.2 to 5.2.3 #35
- Bump color-string from 1.5.3 to 1.9.0 #36
- Upgrades after `ncu -u`: @lumino/datagrid, @lumino/default-theme, @lumino/widgets, core-js, vue (and other dev-dependencies) #37

## 1.1.3 (2021-12-06)

- Bump url-parse from 1.5.1 to 1.5.3 #33
- Fix release checklist Wiki page, re-release now bundle version (thanks to @Lee-42 for reporting in #34) #34

## 1.1.2 (2021-09-29)

- Bump postcss from 7.0.32 to 7.0.36 #30
- Bump path-parse from 1.0.6 to 1.0.7 #31
- Bump tmpl from 1.0.4 to 1.0.5 #32

## 1.1.1 (2021-05-29)

- Bump highlight.js from 9.18.1 to 9.18.5 #19
- Bump ini from 1.3.5 to 1.3.8 #20 
- Bump elliptic from 6.5.3 to 6.5.4 #23
- Bump y18n from 4.0.0 to 4.0.1 #24
- Bump ssri from 6.0.1 to 6.0.2 #25
- Bump url-parse from 1.4.7 to 1.5.1 #26
- Bump hosted-git-info from 2.8.8 to 2.8.9 #27
- Bump browserslist from 4.12.2 to 4.16.6 #28
- Bump dns-packet from 1.3.1 to 1.3.4 #29 

## 1.1.0 (2020-08-27)

- Upgraded dependencies via ncu -u (only non-dev dependency updated
was @lumino/datagrid, from 0.9.1 to 0.10.0)
- Add support for users to define their own tab titles, allowing for
dynamic tab titles

## 1.0.0 (2020-07-04)

- Added tests
- Added CI
- Made the code into a vue library (target/bundle)
- Transferred to github.com/tupilabs organization
- Created tupilabs NPM organization
- First release to NPM

## 0.2 (2020-06-27)

- Removed `VueComponentWrapper` simplifying code
- Using the default `<slot></slot>` wrapped in a `<div v-show=false>`
and syncing components and DOM elements via events
- Code now is almost ready to be used as a component directly, without
the need to copy it and adapt to other projects (which should still
be possible afterwards too)

## 0.1 (2020-02-22)

- Initial version, with a `VueComponentWrapper` wrapper component that
handled the syncing of Vue components and Lumino DOM elements.
- Link added to the Lumino project
