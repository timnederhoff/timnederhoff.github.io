---
layout: default
title: Vision
---

# Testflow 2.0
see https://github.com/timnederhoff/TestFlow-2.0

# testcode cannot be more complex than source code: use out of the box of your frameworks/test wares functionality as much as possible
Here: explanation

# don't cheat: the testflow follows the user's path and then the data's path'

Here: explanation

# only release and deploy if tests are passed/Keep your test environment operational
If tests fail, it's unsafe to continue to release and deployment as no one benefits from an unknown version. If you're sure you can implement a 'force release/deploy' button for cases you verified that a build is save to release/deploy.

# Use tools and frameworks the way they're designed
Too often I see failing pipelines (or, falsely passing pipelines with undesired results) as a result of poorly crafted setup. By working around with complex scripts and specific pieces of code, you're making the setup prone to failure when tooling updates.
HERE: example
