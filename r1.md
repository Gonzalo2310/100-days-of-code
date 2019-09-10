# #100DaysOfCode Round 1 - Infogon

The log of my #100DaysOfCode challenge. Started on September 9, Monday ,2019.

## Log (details in [log](log.md)) (code [Edit i18n](https://github.com/Gonzalo2310/i18nEdit))

### R1

#### Project:

Editor for i18n json files. 

#### Reason:
A publisher with the necessary conditions has not been found. 

* To edit related files. 
* Respect file formats.
* Recognize index.js as a possible field container or importer of other files.
* Recognize fields within text strings.

#### Problems:

* Dynamic loading of the contents of the modified files. 
* Writing changes in files (this must be done from the back but does not use the same import format of the front)
* Search for content in all related languages for content updates.
* Control of accents, quotation marks, and variables (which should not alter the name).
* HTML markup recognition.
* Possibility of introducing HTML marks manually (at least in this version).

#### Objectives:

* Solve all the problems presented.
* Carry out the functionalities in js Vanilla in such a way that they are portable.
* Develop Vuejs tests. 
* Develop Vanilla js tests.
* Develop CI functionalities in order to test the editor online.
* Creation of .env file for customized variables of each project.

#### Resources:

[Vue Cli](https://cli.vuejs.org/)

[Vuejs](https://vuejs.org/)

[Js Vanilla](http://vanilla-js.com/)

[HTML 5](https://developer.mozilla.org/en-US/docs/HTML/HTML5)

[Scss](https://sass-lang.com/documentation/syntax)

[Element-UI](https://element.eleme.io/#/en-US/)

[Git]([https://git-scm.com](https://git-scm.com/))

[ESLint](https://eslint.org/)

[Axios](https://github.com/axios/axios)

[Node-fs](https://node.readthedocs.io/en/latest/api/fs/)

[Node-path](https://nodejs.dev/the-nodejs-path-module)

[Node cors](https://github.com/expressjs/cors)

[express-vue](https://github.com/express-vue/express-vue)

[Babel](https://babeljs.io/)

[Jest](https://jestjs.io/)

[NightWatch](https://nightwatchjs.org/)

[Node 12.x](https://nodejs.org/en/)

[yarn](https://yarnpkg.com/lang/en/) 

#### MVP (Minimum viable product):

* Language recognition by main folders.
* Search of contents differentiating reference and real way: 
  * Example: en/user/error/index.js => notFound: "User not found".
    * Reference: language/user/error/notFound
    * Real Path: languaje/user/error/index.js => notFound

* Search for content by field name or by field content.
* Filters by languages.
* Show all languages when editing (for cited text references)
* Maintain a backup of changes (configurable backup level)
* To revert historical changes.
* Log of changes made.
* Control of accents and conflicting characters.
* Allow and avoid the translation of HTML marks.
* Variable recognition. 
* Warning in HTML changes or variables.
* Update of changes.

#### Extra:

* Configurable front languages (editor).
* Editor configuration admin zone.
* To be able to add languages to the project using as base an existing one.
* To be able to add new fields in the files. (In all available languages)
* Duplicate content search. And possibility of substitution.
* Search of contents not used in the project.
* Search for possible erroneous references (erroneous semantics).
* Search for untranslated strings in the project. And possibility of substitution.
* Online translator suggestions.

