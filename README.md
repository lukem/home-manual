# Home Manual

## Introduction

This repository contains advice and templates for documenting your home in a
*Home manual*, for yourself as well as any other users of your home.

My goal is to encourage you to document important information about living in
your home, for day-to-day purposes as well as when emergencies occur.

This repository contains templates outlining the recommended information to
include in your *Home manual*.

Luke Mewburn, Luke@Mewburn.net.
13 February 2026.

## Motivation

Over recent years a couple of friends have unexpectedly lost their partners.
Aside from their grief, important knowledge about how their home operated was
lost or hard to find.

My beloved wife Inger (AKA [Thesis Whisperer](https://thesiswhisperer.com)) and
I discussed me writing a "*Home manual*" documenting important and useful
information about our home, because most of the information was either in my
head or spread across years of email messages in my personal mail account.

I wrote the initial version of our *Home manual* over the summer break of
December 2022 - January 2023.
The manual has since been converted to **mdbook**, and it's currently 52
pages of documentation and diagrams.

## Templates

### 1. [mdbook template](template/SUMMARY.md)

This is a template based on my current practice (as at Feburary 2026).
The manual is a **git** repository containing a tree of folders in (GitHub
compatible) Markdown format, including the link and anchor slug format.

This template *Home manual* is in **mdbook** format.

The following tools should be installed:

- [mdbook](https://rust-lang.github.io/mdBook/)
- [mdbook-lint](https://joshrotenberg.com/mdbook-lint/)
- [mdbook-pandoc](https://github.com/max-heller/mdbook-pandoc)
- [pandoc](https://pandoc.org/installing.html)

For example, using **rust**'s **cargo** and **brew** on macOS:

```sh
cargo install mdbook mdbook-lint mdbook-numbering mdbook-pandoc
brew install pandoc librsvg python homebrew/cask/basictex
```

To render locally into a web browser, use

```sh
mdbook serve --open .
```

To generate a PDF in `.book/pandoc/pdf/HomeManual.pdf`, use:

```sh
mdbook build
```

### 2. [Home-Manual-Template.md](Home-Manual-Template.md)

Original *Home manual* Template, in Markdown.

## General advice

- Keep the *Home manual* up to date.
- Documentation:
  - Server provider information:
    - Contact information.
    - Account and/or customer numbers.
    - Plan details (if relevant).
    - Password manager entry.
  - Device information:
    - Description, model, location, serial number, purchase date, warranty, expiry date, supplier, installer (if separate to supplier).
  - Don't store sensitive information such as passwords - use a [password manager](#password-managers).
    A reference to the relevant entry in the password manager entry is sensible.
- Diagrams:
  - These don't need to be architectural, construction, or engineering grade. The important point is to contain information useful to lay-people. My diagrams are specifically "not to scale".
  - Maintain layers (if your diagram software supports layers) for:
    - External property plan.
    - Internal home plan.
    - Services: electricity, garden, IoT, lights, network, water/sewer, (etc.)
- Software:
  - Use software and tools that are useable and maintainable by your household. I've migrated to using an **mdbook** setup with the repository hosted in GitHub.
  - Export to PDF and store in well-known locations.
  - Print the manual and store in a well-known location. Even just the first few pages with emergency and critical information can be helpful.

## Password managers

Use a good password manager for your personal passwords and information.

Setup a "Shared family" section (shared with your family) with entries including:

- Household services (energy, internet, water).
- Insurance documents (home, car).
- Wifi passwords.

We currently use **1Password**, but other password managers such as
**Bitwarden** are also well regarded.
