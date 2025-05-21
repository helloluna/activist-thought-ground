_config.yml

---
title: "Activist Thought Ground"
description: "Philosophical reflections on animal ethics, structural violence, and the moral position of refusal."
baseurl: ""
url: "https://helloluna.github.io"
remote_theme: "mmistakes/minimal-mistakes"
plugins:
  - jekyll-remote-theme
  - jekyll-include-cache

# Appearance
minimal_mistakes_skin: "default"
markdown: kramdown
kramdown:
  input: GFM

# Build settings
collections:
  chapters:
    output: true
    permalink: /:collection/:name/

defaults:
  - scope:
      path: ""
      type: chapters
    values:
      layout: single
      toc: true
      toc_sticky: true
      read_time: true
      author_profile: false
      comments: false

index.md

---
layout: home
title: "Activist Thought Ground"
permalink: /
---

This is a reflective archive on the ethical ground of animal advocacy.

It records acts of thought that arise not from academic duty, but from existential obligation — a refusal to forget, to silence, to become numb. Each entry is a fragment of moral orientation in the face of structural violence and systemic erasure.

## Chapters

- [Sentience vs. Utilitarian Calculus](sentience_vs_utilitarianism.md) — Why pain, not productivity, must define worth.
- [Civil Disobedience and the Ethics of Animal Liberation](civil_disobedience.md) — On when breaking the law becomes a moral obligation in the face of systemic injustice.
- [Freedom, Flesh, and the Myth of Consent](freedom_and_flesh.md) — On agency under domestication.
- [The Problem of Silence](the_problem_of_silence.md) — What it means to witness ethically.
- [The City as Killing Structure](city_as_killing_structure.md) — Reflections on urban environments and invisible suffering.
- [Hope and Failure in Ethical Action](hope_and_failure.md) — Why we act even when we expect to lose.
