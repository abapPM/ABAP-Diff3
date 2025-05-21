![Version](https://img.shields.io/endpoint?url=https://shield.abappm.com/github/abapPM/ABAP-Diff3/src/zcl_diff3.clas.abap/c_version&label=Version&color=blue)

[![License](https://img.shields.io/github/license/abapPM/ABAP-Diff3?label=License&color=success)](LICENSE)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?color=success)](https://github.com/abapPM/.github/blob/main/CODE_OF_CONDUCT.md)
[![REUSE Status](https://api.reuse.software/badge/github.com/abapPM/ABAP-Diff3)](https://api.reuse.software/info/github.com/abapPM/ABAP-Diff3)

# ABAP Diff3

Library to highlight the content difference between two or three string-tables (diff3).

NO WARRANTIES, [MIT License](LICENSE)

[ABAP-Diff3-Tests](https://github.com/abapPM/ABAP-Diff3-Tests) contains various test cases

## Diff3 Utils

This is a library to find differences between two string tables, generate and apply patches, and perform 3-way merging between an original and two changed string tables. It contains similar functionality to the [GNU Diffutils](https://www.gnu.org/software/diffutils/manual/diffutils.html) tools.

## Prerequisites

SAP Basis 7.4 or higher

## Installation

You can install ABAP Diff3 using [abapGit](https://github.com/abapGit/abapGit) either creating a new online repository for `https://github.com/abapPM/ABAP-Diff3` or downloading the repository [ZIP file](https://github.com/abapPM/ABAP-Diff3/archive/main.zip) and creating a new offline repository.

Recommended SAP package: `$DIFF3`.

## Usage

The [test classes](https://github.com/abapPM/ABAP-Diff3/blob/main/src/zcl_diff3.clas.testclasses.abap) contain examples for all interface methods.

## Contributions

All contributions are welcome! Read our [Contribution Guidelines](CONTRIBUTING.md), fork this repo, and create a pull request.

## Attribution

The implementation is a port of node-diff3 (https://github.com/bhousel/node-diff3, MIT license).

## About

Made with ❤ in Canada

Copyright 2025 apm.to Inc. <https://apm.to>

Follow [@marcf.be](https://bsky.app/profile/marcf.be) on Blueksy and [@marcfbe](https://linkedin.com/in/marcfbe) or LinkedIn

