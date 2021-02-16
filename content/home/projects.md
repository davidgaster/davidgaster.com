---
# An instance of the Accomplishments widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Projects'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
- title: Learning Extended Enterprise
  date_end: ""
  date_start: "2020-12-15"
  description: |2-
    * Worked with multiple cross functional teams to deliver the integrations which are the backbone of Workday's new and improved learning platform.
    * These integrations are responsible for managing all 60,000 learners' curriculums, certifications, and affiliations.
    * Our team enabled Single Sign-On (SSO) for all customers and achieved 18,000 unique successful logins within the first 24 hours.
    * The iValidator static code analysis project helped to catch many errors that would have arised during the release.
  organization: Workday

- title: iValidator and CI/CD
  date_end: ""
  date_start: "2020-10-01"
  description: |2-
    * This is one of my most impactful projects at Workday, and is expected to save $1M+.
    * I built a static code analysis tool that can validate any SnapLogic project to prevent errors during production deployments.
    * It is now used across all projects in Business Technology as a validation step in our new CI/CD pipeline that I built using Jenkins. 
    * This tool saves significant time and technical debt during all of our code migrations.
    * I showcased my work to the whole Business Technology organization including the Chief Operating Officer of Workday!
  organization: Workday

- title: 'MAC Address Tracker'
  date_end: ""
  date_start: "2020-07-01"
  description: |2-
    * I developed an end-to-end centralized management website that interfaces with Aruba's ClearPass API's. 
    * It allows seamless modification of static host lists (whitelisted or blacklisted MAC addresses) across teams at Workday. 
    * This was the first website I had ever built from the ground up, which is awesome! I learned React, Node.js, and various Amazon Web Services - EC2, Lambda, S3, Secrets Manager, API Gateway and RDS.
  organization: Workday

- title: 'Identity Token Generator'
  date_end: ""
  date_start: "2020-05-01"
  description: |2-
    * When a user scans a QR code to be admitted to the Workday Rising conference, this integration authorizes that request.
    * This was part of the migration of all integrations in Mulesoft to SnapLogic.
    * I refactored and simplified the overall system design, improving maintainability and reducing technical debt.
  organization: Workday

- title: 'Query Parser'
  date_end: ""
  date_start: "2019-07-01"
  description: |2-
    * This project helped with migrating SQL queries from one legacy data warehouse to another, such as from MySQL to PostgreSQL. 
    * I created an abstract syntax tree of SQL in Haskell to parse queries betweend different SQL dialects, facilitating the query migration.
    * The parser translates select, from, where, groupby, having, orderby, and joins.
  organization: Blitzz

- title: "Fox Programming Language"
  date_end: ""
  date_start: "2019-06-01"
  description: |2-
    * Using Haskell, I built a programming language and compiler similar to Python.
    * The language supports complex programming constructs including type inference, function calls, recursion, data structures (lists, tuples, trees), static/runtime type checking, and a garbage collection system in C.
  organization: UC San Diego

- title: "Ngram Machine Learning Model"
  date_end: ""
  date_start: "2019-03-01"
  description: |2-
    * Using the Python NLTK library, I built trigram, bigram, and unigram language models. 
    * I implemented Laplace smoothing and analyzed the improvements on the perplexity of each dataset. 
    * After tuning hyperparameters, the model has the ability to auto‐generate real sentences.
  organization: UC San Diego
---