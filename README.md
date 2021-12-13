<!--- SPDX-License-Identifier: CC-BY-4.0 -->
<!--- SPDX-FileCopyrightText: 2021 Sebastian Crane <seabass-labrax@gmx.com> -->

# TV Instructions

This repository contains LaTeX sources for generating an instructions document for my TV setup. Whilst the precise details of any such setup are bound to be different, this might still serve as either a template on which to base your own documents, or simply to demonstrate the difficulties of getting 40 years of home entertainment technology to work together on a single CRT television!

Three things that one learns from attempting such a feat are that:

1. The more recent the device is, the more likely it is to assume total control of the signal if at all possible.

2. Analogue devices can get 'locked into' a state until the power is cycled, despite (ostensibly) having no memory.

3. SCART is the least sensible connector design that could be conceived!

# Generating a PDF

Make sure you have `texlive` installed, then run `pdflatex -interaction=nonstopmode src/instructions.latex`.
