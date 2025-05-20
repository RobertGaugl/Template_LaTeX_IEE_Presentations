# IEE LaTeX Presentation Template

This repository contains a **LaTeX Beamer presentation template** developed by the Institute of Electricity Economics and Energy Innovation (IEE). It provides a consistent and professional design style for presentations related to the institute's courses, lectures, and research activities.

<p align="center">
  <img src="figures/Slides.png" alt="Example Slides" width="80%" /></br>
  <b>Figure 1.</b> Some example slides.
</p>

## How to use?
1) Download the ZIP file by clicking the green "**Code**" button and selecting "**Download ZIP**".
2) Depending on your LaTeX editor:
   - **Overleaf**: Click **New Project** > **Upload Project**, then select the downloaded ZIP file.
   - **Other LaTeX editors**: Extract the ZIP file and open the files in your preferred editor.
3) Read the content of the template carefully. It explains the rules for designing a presentation at the IEE and provides helpful tips and tricks.

## Overview

The template includes:

- A custom Beamer theme tailored to IEE's branding and style guidelines.
- Design guidelines to ensure consistent use of colors, fonts, and layout.
- Example slides demonstrating key content structures such as definitions, tasks, goals, and use cases.

## Features

- Use the `\begin{coloredblock}` environment to easily create visually distinct boxes—with or without a title.
- Add subtle background effects with `\insertfadedpicture` to enhance visual appeal.
- Conveniently place source references in the bottom left corner using the `\addsource` command.
- Create consistent title and closing slides with `\maketitleslide` and `\closingslide`. These commands automatically adapt to the selected language.

## Release Notes
- **2025-05-19:**
   - Add new box style with icon on the left `\begin{coloredblockleft}`
   - Fixed calculation of box height 
   - Change function coloredblocks and add option to customize padding.
   - Optionally display Beamer navigation buttons in the lower left corner (can be enabled in the Options section).
   - Include new list styles (romanenumerate, tugromanenumerate (tighter spacing), boxromanenumerate)
   - Include a section on Overlays to explain how to reveal content step-by-step.
   - Update attribution text for picture used in agenda slide to inlcude links.
   - Set UrlFont to use normal font instead of monospaced font.
- **2025-05-18:**
   - Fix showing `\begin{coloredblock}{turquoise}` on slide Dark Boxes with Title instead of `\begin{coloredblockdark}{turquoise}`.
   - Add highlight to table.
   - Add description that caption text of `\insertfadedpicture` is optional.
   - Deactivate "Sponsored by" on title page.
   - Add function `\addsource` to easily add a source text to the bottom right corner of the slide.
   - Add attribution for fontawesome icons.
- **2025-05-18:**
   - First upload