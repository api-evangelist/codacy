---
title: "Introducing Codacy Skills (Part 3): Let your agent set up test coverage"
url: "https://blog.codacy.com/introducing-codacy-skills-part-3-let-your-agent-set-up-test-coverage"
date: "2026-08-06"
author: "Alejandro Rizzo"
feed_url: "https://blog.codacy.com/rss.xml"
---
Codacy tracks four metrics on a repository: issues, duplication, complexity, and coverage. Three of them we work out by analysing the code. Coverage is the one we cannot, because knowing which lines your tests reach means running the tests, and your tests run in your pipeline rather than ours.
