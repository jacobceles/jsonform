JSON Form
=========

![MIT license](https://img.shields.io/badge/License-MIT-blue.svg?longCache=true)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true)
![Maintained](https://img.shields.io/badge/Maintained-yes-brightgreen.svg?longCache=true)
![Release](https://img.shields.io/github/release/jsonform/jsonform.svg)
![NPM: released](https://img.shields.io/npm/v/jsonform.svg)


The JSON Form library is a JavaScript client-side library that takes a
structured data model defined using [JSON Schema](http://json-schema.org/) as
input and returns a [Bootstrap 3](https://getbootstrap.com/docs/3.3/)-friendly
HTML form that matches the schema.

The generated HTML form includes client-side validation logic that provides direct inline feedback to the user upon form submission (provided a JSON Schema validator is available). If values are valid, the JSON Form library uses submitted values to create the JavaScript data structure that matches the data model.

The layout of the generated HTML form may be entirely fine-tuned through
a simple declarative mechanism.


Changes in the forked version
------------------------------

[Decoupled/Custom implementation](https://github.com/jacobceles/jsonform/tree/master/decoupled_project_implementation) of [jsonform](https://github.com/jsonform/jsonform) is a simpler version of the original project, with a better structure and enables easier upgrades. The custom implementation is in the form of a standalone project. You can find it in the [decoupled_project_implementation](https://github.com/jacobceles/jsonform/tree/master/decoupled_project_implementation) folder. A quick glance into the changes:
* Decoupled source and form components - Enables users to enhance JSON without touching code.
* Decoupled Bootstrap CSS and Custom CSS - Enables easy bootstrap upgrade.
* Decoupled custom JS and upgradable ones - Enables easy upgrade.
* A way easier implementation of the original porject - let's you create your own version with very minimal changes.


License
-------

The JSON Form library is licensed under the [MIT license](https://raw.github.com/joshfire/jsonform/master/LICENSE).

All the libraries that JSON Form may depend on are licensed under the MIT license, except for the JSON Schema Validator, licensed under the BSD 3 Clause license and the ACE editor licensed under the Mozilla tri-license (MPL/GPL/LGPL).
