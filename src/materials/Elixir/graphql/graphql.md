---
path: '/materials/graphql'
type: 'GitHub'
img: './screenshot.png'
material:
  title: 'graphql'
  url: 'https://github.com/asonge/graphql'
  github_url: 'https://github.com/asonge/graphql'
  subscribers_count: '9'
  stargazers_count: '88'
  tags: ['']
  subtitle: 'Elixir graphql library'
  clone_url: 'https://github.com/asonge/graphql.git'
  ssh_url: 'git@github.com:asonge/graphql.git'
  pushed_at: '2015-07-12T19:36:20Z'
  updated_at: '2019-01-27T15:45:21Z'
  author:
    name: 'asonge'
    avatar: 'https://avatars3.githubusercontent.com/u/90809?v=4'
    github_url: 'https://github.com/asonge'
  latestRelease:
    tag_name: null
    name: null
    url: null
    created_at: null
---
Graphql [![Build Status](https://secure.travis-ci.org/asonge/graphql.svg?branch=master 'Build Status')](http://travis-ci.org/asonge/graphql) [![Coverage Status](https://coveralls.io/repos/asonge/graphql/badge.svg?branch=master&service=github)](https://coveralls.io/github/asonge/graphql?branch=master)
=======

A tool to compile graphql queries into native Elixir.

The goal is for people to define their schemas in Elixir with callbacks
while the library handles the asynchronous requests, composing the results
together, and sending a reply to the query. It would be a great benefit to
have a babeljs plugin be able to replace graphql es6-templated strings and
leave behind a cryptographic checksum of the query, and then compile that
those queries on the server.

For right now, this project focuses mainly on getting the very basics up and running.

References
---

Specification: http://facebook.github.io/graphql/

Reference Implementation: https://github.com/graphql/graphql-js/


Status
---
Sections from the RFC for the parser that are complete.
- [x] 8. Grammar
  - [x] 8.1 Tokens
    - [x] 8.1.1 Ignored Source
  - [x] 8.2 Syntax
    - [x] 8.2.1 Document
    - [x] 8.2.2 Operations
    - [x] 8.2.3 Fragments
    - [x] 8.2.4 Values
      - [x] 8.2.4.1 Array Value
      - [x] 8.2.4.2 Object Value
    - [x] 8.2.5 Directives
    - [x] 8.2.6 Types
