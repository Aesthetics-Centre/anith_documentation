---
title: Documentation
---

# 📚 Documentation Overview

Welcome to the documentation section! Here you'll find notes, guides, and reference
materials organized by topic.

<hr class="section-divider">

## 📂 Available Documents

<!-- ============================================================
     INSTRUCTIONS: Each doc-card uses a background image.
     Replace YOUR_FILE_ID with your Google Drive image File ID.
     To get the File ID: Share image → "Anyone with link" → copy
     the ID from the URL after /d/
     ============================================================ -->

<div class="card-grid" markdown>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1lJF64u4UmLNtrHdB5WT4IilpH4-UBSXz&sz=w800');" markdown>

### 🚀 Expectations

A clear expectations and access plan draft for all user and core team member.

[:octicons-arrow-right-24: Read More](expectation.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1lGzZZEypeHQ6VM1ksoVQjZuw2TQ7mPaG&sz=w800');" markdown>

### 🚀 Getting Started Guide

A showcase of all the Markdown features you can use in your documentation.

[:octicons-arrow-right-24: Read Guide](getting-started.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1Lj5d11XVvTUJN1gPjvFBOS0ZFoCAJX6v&sz=w800');" markdown>

### 🚀 Software Installation

Mostly used software in Fab Lab

[:octicons-arrow-right-24: Read Guide](installation.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1vckkKiw4VYqrtBy6Klcx49GVrRNAu06G&sz=w800');" markdown>

### 🚀 Image Stacking

Image stacking with Siril and StarMet

[:octicons-arrow-right-24: Read Guide](image_statcking_Siril.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1I5p0B1CN_z-YIJRhbshPFh2YHMjQHOmj&sz=w800');" markdown>

### 🚀 Panoptes Basics

This is documentation on using the Panoptes Unit.

[:octicons-arrow-right-24: Read Guide](panoptes_basic.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1BhvJVS9HMZIB7ECbB4y-IOgH7cQfxbeU&sz=w800');" markdown>

### 🚀 Auto Wisp

This is documentation is about working on light curves.

[:octicons-arrow-right-24: Read Guide](auto_wisp.md)

</div>

<div class="doc-card" style="background-image: url('https://gitlab.com/anithghalley/robotics_for_students/-/raw/main/Images/robotics_images/led_resistor_simulation.png?ref_type=heads');" markdown>

### 🚀 TinkerCad Simulation

Documentation on how to simulate in Thinkercad Circuit

[:octicons-arrow-right-24: Read More](basic_simulation.md)

</div>

<div class="doc-card" style="background-image: url('https://gitlab.com/anithghalley/robotics_for_students/-/raw/main/Images/robotics_images/resistance.png?ref_type=heads');" markdown>

### 🚀 Blinking LED on Arduino

Documentation on how to control an LED

[:octicons-arrow-right-24: Read More](led_blink.md)

</div>

<div class="doc-card" style="background-image: url('https://fabacademy.org/2025/labs/dgi/students/tsheyang-tshewang/images/week04/a_ide.jpg');" markdown>

### 📝 Blank Template

Copy this template to create new documentation pages quickly.

[:octicons-arrow-right-24: View Template](template.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1AsCfjgCw3bjLQo3i22QtAu8UhmYtG4X9&sz=w800');" markdown>

### 🚀 3D Designing

Your first 3D design project.

[:octicons-arrow-right-24: Read Guide](3d_design.md)

</div>

<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=1ZjgRJWL-JIECZ91lsBazkVHkMtzo0-Iu&sz=w800');" markdown>

### 🚀 2.5 D CNC Frame

2.5 D milling with CNC shopbot

[:octicons-arrow-right-24: Read Guide](CNC_Frame.md)

</div>

</div>

---

## ➕ How to Add New Documents

!!! info "Adding a New Page"

    1. **Create** a new `.md` file in the `docs/documentation/` folder  
       _(e.g., `my-new-topic.md`)_

    2. **Copy** the content from `template.md` as a starting point

    3. **Add** your new page to `mkdocs.yml` under the `Documentation` section:

        ```yaml
        nav:
          - Documentation:
              - Overview: documentation/index.md
              - Getting Started Guide: documentation/getting-started.md
              - "📝 Blank Template": documentation/template.md
              - My New Topic: documentation/my-new-topic.md    # ← add here
        ```

    4. **Save** and run `mkdocs serve` to see your changes!
