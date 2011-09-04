# Overview

This bundle is designed to help you write JavaScript documentation using [JsDoc Toolkit][jsdoc]. It contains commands for running JsDoc Toolkit on one or more JavaScript files in TextMate as well as snippets for each of the tags that JsDoc Toolkit supports. The bundle currently uses JsDoc Toolkit 2.4.0.

JsDoc Toolkit is an application, written in JavaScript, for automatically generating template-formatted, multi-page HTML (or XML, JSON, or any other text-based) documentation from commented JavaScript source code.

## Installing from GitHub

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/csaccheri/JSDoc-Toolkit.tmbundle.git "JSDoc Toolkit.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Commands

* **Document with JsDoc Toolkit** (⌃⌘D)
Generates HTML documentation from commented JavaScript source code using JsDoc Toolkit and displays it in TextMate's Web Preview window. You can generate documentation from a single file, multiple selected files, or an entire directory.

* **Edit JsDoc Toolkit Configuration** (⌃⌘D)
Opens the configuration files used by the bundle to run JsDoc Toolkit. You can edit this file to change configuration options, such as whether to include private methods, use a different output template, etc. Read about [JsDoc Toolkit command line options][jsdop] for more information on each option.

* **View Tag Reference** (⌃⌘D)
Opens the [JsDoc Toolkit tag reference][jsdot] in TextMate's Web Preview window.

## Snippets

This bundle includes a number of snippets to help you write JsDoc Toolkit-friendly comments.  The `docblock` snippet will create a documentation comment block (starting with `/**`), while the other snippets are specific to the various tags JsDoc Toolkit supports.

Read the [JsDoc Toolkit tag reference][jsdot] for more information on each tag.

## Licenses

* **[JsDoc Toolkit][jsdoc]** ([MIT License][mit])

[mit]:    http://www.opensource.org/licenses/mit-license
[jsdoc]:  http://code.google.com/p/jsdoc-toolkit/
[jsdop]:  http://code.google.com/p/jsdoc-toolkit/wiki/CommandlineOptions
[jsdot]:  http://code.google.com/p/jsdoc-toolkit/wiki/TagReference