---
layout: post
title: "Jak instruować LLM do używania ARIA Authoring Practices Guide"
description: "Eric W. Bailey pokazuje, które fragmenty APG można przekazywać modelom językowym, a które lepiej pominąć"
date: 2026-02-26
tags: [ARIA, dostępność, LLM, sztuczna-inteligencja, APG]
---

Eric W. Bailey opublikował praktyczny artykuł o poważnym problemie: ARIA Authoring Practices Guide (APG) był tworzony jako katalog możliwości ARIA, nie jako wzorzec dobrych praktyk. Przykłady kodu są nierównej jakości, faworyzują ARIA nad semantycznym HTML i bywają nieaktualne.

Gdy LLM są trenowane na tych treściach – utrwalają i powielają te problemy na dużą skalę.

Bailey proponuje konkretne rozwiązanie: zamiast ignorować APG całkowicie, być **selektywnym** w tym, co się modelom udostępnia. Sekcje opisujące zachowanie klawiatury i koncepcje interakcji – tak. Przykłady kodu i linki do CodePen – nie.

Warto przeczytać w całości: **[Here's How to Instruct a LLM to Reference the ARIA Authoring Practices Guide](https://ericwbailey.website/published/heres-how-to-instruct-a-llm-to-reference-the-aria-authoring-practices-guide/)** (Eric W. Bailey)
