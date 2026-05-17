---
title: "Common anti-patterns in Go"
description: "A short pointer to my DeepSource article on Go anti-patterns and writing maintainable Go code."
publishDate: "2021-03-18"
tags: ["go", "deepsource"]
canonicalURL: "https://deepsource.com/blog/common-antipatterns-in-go"
draft: false
---

I wrote this article for DeepSource as a practical checklist of Go anti-patterns that are easy to miss in day-to-day code review.

It covers small but meaningful issues like exported functions returning unexported types, unnecessary blank identifiers, redundant `make` arguments, useless `return` and `break` statements, overcomplicated function literals, single-case `select` statements, and `context.Context` argument placement.

Read the original article on DeepSource:

[Common anti-patterns in Go](https://deepsource.com/blog/common-antipatterns-in-go)
