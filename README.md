# Snakemake Language Support

Provides basic language support and snippets for [Snakemake](https://snakemake.readthedocs.io) files (Snakefile, *.smk).

This is an unofficial extension and I am not affiliated with the [Snakemake](https://snakemake.readthedocs.io) project, but since I use Snakemake daily (it is truly an excellent tool) I wanted better support for it in VSCode and in publishing this plugin I hope that others might get some value from it as well.

This is still very much in alpha, so it's likely that not everything works.

Feedback, suggestions, and contributions are very welcome!

## Features

- Syntax definitions based on Python with added Snakemake grammar
- Language rules based on Python with added Snakemake grammar
- Rule snippet

## Supported Syntax

- **Keywords**
  <!-- Rule types -->
  - [x] rule
  - [x] subworkflow
  - [x] checkpoint
  <!-- Configs -->
  - [x] include
  - [x] configfile
  - [x] snakefile
  - [x] workdir
  - [x] ruleorder
  - [x] onsuccess
  - [x] onerror
  - [x] onstart
  <!-- Rule Parameters -->
  - [x] input
  - [x] output
  - [x] params
  - [x] log
  - [x] priority
  - [x] shadow
  - [x] group
  - [x] benchmark
  - [x] message
  - [x] threads
  - [x] resources
  - [x] version
  - [x] run
  - [x] shell
  - [x] script
  - [x] cwl
  - [x] conda
  - [x] wildcard_constraints
  - [x] wrapper
- **Functions**
  - [x] expand
  - [x] unpack
  - [x] ancient
  - [x] directory
  - [x] temp
  - [x] protected
  - [x] touch
  - [x] pipe
- **Other**
  - [ ] String substitutions `"command {input}"`
  - [ ] Wildcard constraints inside string substitutions `"{sample,[A-Za-z0-9]+}"`

<!--
- **Parameters**
  - [ ] threads
  - [ ] memory
-->

## Snakemake Support for other Editors

- [vim-snakemake](https://github.com/ivan-krukov/vim-snakemake)
