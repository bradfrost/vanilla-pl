# Vanilla Pattern Lab

Vanilla Pattern Lab is a barebones UI starter kit that uses [Pattern Lab Node](https://github.com/pattern-lab/edition-node-gulp).

## Installing

In order to get Pattern Lab up and running in your local environment, run the following commands in your terminal:

1. `git clone https://github.com/bradfrost/vanilla-pl.git && cd vanilla-pl`
2. If gulp is not installed on your computer, install it using `npm install gulp-cli -g` in the command line.
3. In the command line, navigate to the root of the project, then run `npm install` to download the project's dependencies.
4. Run `gulp patternlab:serve` to build Pattern Lab and watch for changes.
5. Visit `http://localhost:3000/` in your browser to view Pattern Lab.

## Pattern Lab Documentation

Please view [Pattern Lab's documentation](http://patternlab.io/docs/index.html) for info on how to use the tool.

## Helpful Commands

These are some helpful commands you can use on the command line for working with Pattern Lab.

> Reminder: These commands assume a global installation of gulp 4.X, instead of a local installation.

### List all of the available commands

To list all available commands type:

    gulp patternlab:help

### Generate Pattern Lab

To generate the front-end for Pattern Lab type:

    gulp patternlab:build

### Watch for changes and re-generate Pattern Lab

To watch for changes, re-generate the front-end, and server it via a BrowserSync server, type:

    gulp patternlab:serve

BrowserSync should open [http://localhost:3000](http://localhost:3000)
