# Intro to KiCad

![Pictures\3D-final.png]()

## Overview

Welcome to the **Intro to KiCad** repository. This lab script is designed to introduce the fundamentals of PCB design using KiCad, a powerful and free software suite for electronic design automation (EDA). Throughout this lab, you'll go through the process of creating a **stylophone**, a simple electronic musical instrument, while learning the key steps in PCB design, including schematic creation, footprint assignment, PCB layout, and exporting Gerber files for manufacturing.

This repository contains all necessary libraries, project files, and references to help you complete the lab.

---

## Repository Structure

```bash
intro-to-kicad/
│
├── BOM/                 # Bill of Materials for the Stylophone project
├── Example Project/     # Completed project files for reference
├── Libraries/           # Symbol and footprint libraries
├── Pictures/            # Images for documentation
├── intro-to-kicad-backups/ # Backup files for the project
```

## Prerequisites

Before starting, ensure you have the correct version of KiCad installed. You can download the latest version from KiCad's official website.

You'll also need to install the necessary symbol and footprint libraries included in this repository. See the setup instructions below for details.

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/YorkEngSoc/intro-to-kicad.git
```

2. Install KiCad:
If you don’t have KiCad installed on your system, download it from the official KiCad website.

3. Set up libraries:

    - Open KiCad and go to Preferences > Manage Symbol Libraries.
    - Import the symbol and footprint libraries from the Libraries/ directory in this repository.

4. Open the Project:

    - Navigate to the Example Project/ folder where you cloned the repository and open the project in KiCad.

## Lab Steps Overview

1. Environment Setup:
    - Verify the correct software version is installed.
    - Import necessary symbol and footprint libraries, such as the keyboard symbol and footprint used in the stylophone design.

2. Schematic Design:
    - Add components from the Bill of Materials (BOM) to your schematic.
    - Define power inputs, connect components, and label nets for clean design.
    - Use the Electrical Rule Check (ERC) to validate your schematic.

3. PCB Layout:
    - Draw the PCB outline and place components according to the recommended layout.
    - Add copper pours and vias as needed.
    - Use the Design Rule Check (DRC) to ensure the board layout meets design requirements.

4. Export Gerber Files:
    - Once the PCB design is complete, export the Gerber and drill files for manufacturing.
    - If you need assistance with fabrication, please contact us via email (see below).

## Feedback and Support

If you have any questions or need assistance, please reach out to the York Engineering Society via email or send a message in our Discord channel.

Please use this [form](https://forms.gle/ekpGPV2yDJBvafvM7) to provide any feedback on this lab script or suggestions for future labs.

---
This repository is part of the [York Engineering Society](https://york.engineering) lab series, created for educational purposes at the University of York.