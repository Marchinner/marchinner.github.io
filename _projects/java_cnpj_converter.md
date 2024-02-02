---
layout: page
title: CNPJ Converter
description: simple program to remove special characters from a text
img: assets/img/projects/tools-project.png
importance: 2
category: java
related_publications: true
github: https://github.com/Marchinner/ConversorCNPJ
---

<hr>

This simple program aims to solve a specific problem
in one of the sectors of the company that deals with customer CNPJs on a daily basis.

The problem is that when the user copies the CNPJ into the system, the same
comes to the clipboard in the format XX.XXX.XXX/0001-XX, however
when reusing the CNPJ as information in another part of the system, the same
implies that the user will type and not paste text, as they enter
automatically places dots, bars and dashes in the correct locations, therefore
When the user pastes the CNPJ in the format above, the entry field
system text ends up 'eating' part of the informed CNPJ, as it exceeds
the correct number of characters, requiring the user to
Manually remove the dots, bars and dashes to leave only the numbers.

## Operation

The user enters the CNPJ in the format XX.XXX.XXX/0001-XX in the first field and clicks
click on the 'Convert' button. The CNPJ converted only into numbers will be automatically
copied to the clipboard, becoming available via 'CTRL+V'.
