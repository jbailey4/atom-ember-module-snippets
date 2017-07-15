# Atom Ember Module Snippets

A collection of snippets for importing Ember javascript modules.

After the [Ember RFC 176](https://github.com/emberjs/rfcs/blob/master/text/0176-javascript-module-api.md) was implemented, Ember moved from globals to javascript modules (i.e. `Ember.Application` -> `import Application from "@ember/application"`). This project aims to provide shortcuts by providing the import statement for each Ember module.

### Install

`apm install ember-module-snippets`

### Usage

Begin typing an Ember module you need, such as `component`, press `Tab`, and the corresponding import statement will be printed for you.

![ ](http://res.cloudinary.com/dvc1fhbvs/image/upload/v1500096970/ember-module-snippets-demo_r9q099.gif "Atom ember module snippet demo")

#### Thanks,

to the project, [ember-rfc176-data](https://github.com/ember-cli/ember-rfc176-data), for a full list of each Ember module and the corresponding import, without that this project would not have been possible.
