---
title: My Open Source Contributions
date: 2024-02-10
categories: [Open Source]
tags: [open-source]
author: gambitier
pin: true
---

![gambitier's Github chart](https://ghchart.rshah.org/gambitier){: width="972" height="589"}

Embarking on the journey of open source contributions has been an exhilarating experience for me. In this blog post, I'll share some highlights of my recent contributions to various projects that resonate with my passion for technology and collaboration.

## Juliaup

Juliaup is a Julia installer and version multiplexer written in Rust.

### Pull Requests

1. **[Improve error message for `juliaup self channel` command](https://github.com/JuliaLang/juliaup/pull/882)**
   - Description: This contribution improves the error message for `juliaup self channel` command
2. **[fix(juliaup): handle timeout error to prevent crash](https://github.com/JuliaLang/juliaup/pull/951)**
   - Description: This contribution fixes the installer crash caused by http timeout error

## Elsa Workflows

Elsa is a robust workflow library designed for executing workflows within any .NET application. It provides flexibility in defining workflows through C# code, a visual designer, or specifying workflows in JSON format.

### Pull Requests

1. **[Allow Database Schema Names to be Editable](https://github.com/elsa-workflows/elsa-core/pull/4072)**
   - Description: This contribution introduces the capability to edit database schema names within Elsa.

2. **[MySQL Support](https://github.com/elsa-workflows/elsa-core/pull/4047)**
   - Description: Added support for MySQL, enhancing the compatibility of Elsa workflows.

3. **[Docker Image: Configurable CORS Policy](https://github.com/elsa-workflows/elsa-core/pull/4022)**
   - Description: Implemented a feature to make CORS policy configurable in the Docker image.

## Zod Extras

Zod Extras is an extension that provides additional functionality on top of the Zod framework.

### Issues

1. **[toNumberPreprocessor Converts Empty String to 0](https://github.com/lokalise/zod-extras/issues/40)**
   - Description: Reported an issue where the toNumberPreprocessor was converting an empty string to 0.

## REANCare Service

REANcare Service is the primary healthcare backend API for REAN Foundation's healthcare software ecosystem.

### Issues

1. **[Incorrect Method Call for Fetching User with Email](https://github.com/REAN-Foundation/reancare-service/issues/9)**
   - Description: Reported an issue related to an incorrect method call when fetching a user with email.

## Serilog.Sinks.Postgresql.Alternative

Serilog.Sinks.Postgresql.Alternative is a library that facilitates saving logging information from Serilog to PostgreSQL.

### Issues

1. **[Fix Docs to Resolve "Unable to Find a Method Called PostgreSql"](https://github.com/serilog-contrib/Serilog.Sinks.Postgresql.Alternative/issues/43)**
   - Description: Reported an issue and provided a solution to resolve the error "Unable to find a method called PostgreSql" in the documentation.

## Django

Django is a high-level Python web framework known for encouraging rapid development and clean, pragmatic design.

### Issues

1. **[Fix docs - IntegrityError: NOT NULL Constraint Failed](https://github.com/django/django/pull/10188)**
   - Description: Reported a documentation-related issue regarding an IntegrityError related to a NOT NULL constraint failure.
