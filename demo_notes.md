# Why use Marp?

## Presentation software, rocks!
* Quick and easy to manipulate media
* Attention grabbing transitions

## Presentation software, sux!
* Standards? Hahahaha, you're joking, right?
* Keynote is platform specific
* Powerpoint has 9? file formats/versions
* Themes can be hard to build

## Some things that make devs :sadpanda:
* Can't (easily) script it
* Can't use source control very effectively
  - Big files with embedded media
  - no diffs
  - might as well use a zipfile
  - Bitkeeper, Mysql, argh
* Hard to publish on the web

## Some things that make devs :unicorn: :rainbow:
* Can use a text editor
* Can put in git
* Can put into automated workflows

## MARP in 10s
* Markdown
* use `\r\n --- \r\n` to break a page

## Features
* themes
* PDF generation
* code highlighting
* math typesetting
* EMOJI SUPPORT

## Under the hood
* Built on `marpit`,
* which extends `markdown-it`
* which supports CommonMark spec and more
* Very similar to GitHub Flavored MarkDown
* its Javascript all the way down

## Format
* One MarkDown file
* YAML front-matter
* Directives
  * Use HTML comments
  * global
  * local (and _spot)

## MARP Tools
* https://web.marp.app (:underconstruction)
* MARP electron app (:deprecated)
* CLI
* VSCode!
