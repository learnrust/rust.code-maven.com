---
title: Rocket - web development with Rust
timestamp: 2023-12-22T12:30:01
author: szabgab
published: true
description: Examples with the Rocket web framework for Rustlang
tags:
    - Rocket
    - web
todo:
    - Hello World! with Rocket, tests in a separate file.
    - Set `content-type` `text/html`
    - Accept dynamic pathes (path parameters)
    - Accept GET parameter
    - Accept POST parameter
    - Cookies
    - Deployment
---

[Rocket](https://rocket.rs/) is one of the web development frameworks for the Rust programming language. It has a nice web site that comes with a nice
tutorial, but for me, to undertand it I needed my own, stand-alone examples. On this page you'll find the list of examples. You can get the full source
code of each one of them from [Rust Maven GitHub repo](https://github.com/szabgab/rust.code-maven.com/) or by following the links above the files.

[Rocket on Crates](https://crates.io/crates/rocket).


* [Hello World! with Rocket](/rocket-hello-world) - `text/plain`
* [Hello World with tests in separate file](/rocket-hello-world-separating-tests) - `test`.
* [Hello World! in HTML](/rocket-hello-world-html) - `RawHtml`, `text/html`, `headers`, `get_one`.
* [Hello World with Tera Templates](/rocket-hello-world-tera-template) - `rocket_dyn_templates`, `Template`, `context!`, `render`, `attach`, `fairing`.
* [Echo using HTTP POST - form handling](/rocket-echo-post) - `POST`, `Form`, `Template`, `header`, `body`, `ContentType::Form`, `Status::UnprocessableEntity`, `422`.
* [Single counter in a plain text file](/rocket-single-counter-in-text-file).
* [Multi-counter using cookies](/rocket-multi-counter-using-cookies) - `CookieJar`, `add`, `get`.
* [Multi counter using encrypted cookies](/rocket-multi-counter-using-encrypted-cookies) - `add_private`, `get_private`, `secret_key`,`Rocket.toml`, `private_cookie`.
* [Liniting issues with Rocket](/rocket-linting) - Clippy
* [Logging in a Rocket-based web application](/rocket-logging) - `log`, `debug!`, `info!`, `warn!`,  `error!`.
