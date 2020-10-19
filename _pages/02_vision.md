---
layout: default
title: Vision
permalink: /vision/
---

## Testflow 2.0
see [my idea on a better test flow on Github](https://github.com/timnederhoff/TestFlow-2.0)

## Rules of thumbs
Below are the statements that I came up with and promised to myself in the past years. 

> testcode cannot be more complex than source code

Use out of the box functionality frameworks/test wares functionality as much as possible

> only release and deploy if tests are passed/Keep your test environment operational

If tests fail, it's unsafe to continue to release and deployment as no one benefits from an unknown version. If you're
sure you can implement a 'force release/deploy' button for cases you verified that a build is save to release/deploy.

> Use tools and frameworks the way they're designed

Too often I see failing pipelines (or, falsely passing pipelines with undesired results) as a result of poorly crafted
setup. By working around with complex scripts and specific pieces of code, you're making the setup prone to failure when
tooling updates.
