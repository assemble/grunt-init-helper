# grunt-init-assemble-helper

> Quickly create helpers for use with Assemble, using [grunt-init][]. Includes README documentation, test files, metadata, bower.json and package.json.

## Quickstart
If you have `grunt-init` and are familiar with using it, `git clone` this repo into the directory that [grunt init](http://gruntjs.com/project-scaffolding#installing-templates) recommends for your operating system. The following is recommended for Windows users.

``` bash
git clone https://github.com/assemble/grunt-init-assemble-helper.git ~/.grunt-init/assemble
```

**Note**: you can make the template available as any name you choose by simply changing the name of the folder that the template is installed into. So instead of `~/.grunt-init/assemble`, you may change the name to `~/.grunt-init/foo` so that the template can be used with the following command: `grunt-init foo`.


Then, in empty directory:

* Run `grunt-init assemble-helper`
* Then `npm i`
* Then `grunt` to test that it works

In the the `test` directory you will find the following files:

* `example.hbs`: this is an example template, which contains code for both an example helper and a starting point for your new custom helper.
* `example.json`: this is the data file used by the helper
* `helper-example.js`: umm...



## Detailed instructions
### Installation
If you haven't already done so, install [Grunt][grunt] and [grunt-init][]: 

``` bash
npm i -g grunt-cli grunt-init
```

Once grunt-init is installed, place this template in your `~/.grunt-init/` directory. It's recommended that you use `git clone` to install this template into that directory as follows:

``` bash
git clone git@github.com:assemble/assemble-init.git ~/.grunt-init/assemble
```

_(Windows users, see [the documentation][grunt-init] for the correct destination directory path)_

To force `grunt-init` to use custom default values, move the `defaults.json` file to your `~/.grunt-init/` directory, and customize the values in that file.



### Usage
Now that `grunt init` is intalled. At the command-line, cd into an empty directory and run `grunt-init assemble` and follow the prompts. You might want to test that it works before you begin customizing the project:

 * Next, run `npm install` to install the project's dependencies.
 * Then, run `grunt` to build the project.

_Note that this template will generate files in the current directory, so be sure to change to a new directory first._

[grunt]: http://gruntjs.com
[grunt-init]: http://gruntjs.com/project-scaffolding#custom-templates


## Related info

* [handlebars-helpers](https://github.com/assemble/handlebars-helpers)
* [Assemble's documentation](http://assemble.io)
* [assemble-less](https://github.com/assemble/assemble-less)
* [assemble-examples](https://github.com/assemble/assemble-examples)