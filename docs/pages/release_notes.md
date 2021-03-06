---
title: PMD Release Notes
permalink: pmd_release_notes.html
keywords: changelog, release notes
---

## ????? - 6.7.0-SNAPSHOT

The PMD team is pleased to announce PMD 6.7.0.

This is a minor release.

### Table Of Contents

* [New and noteworthy](#new-and-noteworthy)
    *   [New Rules](#new-rules)
* [Fixed Issues](#fixed-issues)
* [API Changes](#api-changes)
* [External Contributions](#external-contributions)

### New and noteworthy

#### New Rules

*   The new PL/SQL rule [`ForLoopNaming`](pmd_rules_plsql_codestyle.html#forloopnaming) (`plsql-codestyle`)
    enforces a naming convention for "for loops". Both "cursor for loops" and "index for loops" are covered.
    The rule can be customized via patterns. By default, short variable names are reported.

### Fixed Issues

*   java-errorprone
    *   [#1078](https://github.com/pmd/pmd/issues/1078): \[java] MissingSerialVersionUID rule does not seem to catch inherited classes
*   plsql
    *   [#681](https://github.com/pmd/pmd/issues/681): \[plsql] Parse error with Cursor For Loop

### API Changes

### External Contributions

*   [#1254](https://github.com/pmd/pmd/pull/1254): \[ci] \[GSoC] Integrating the danger and pmdtester to travis CI - [BBG](https://github.com/djydewang)
*   [#1258](https://github.com/pmd/pmd/pull/1258): \[java] Use typeof in MissingSerialVersionUID - [krichter722](https://github.com/krichter722)
*   [#1264](https://github.com/pmd/pmd/pull/1264): \[cpp] Fix NullPointerException in CPPTokenizer:99 - [Rafael Cortês](https://github.com/mrfyda)
