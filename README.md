# ClimbFlow

**A Rhino 8 tool for climbing wall panelization and installation documentation.**

ClimbFlow is a workflow-oriented tool developed from a practical need in climbing wall design. It helps organize the process of dividing a 3D climbing wall surface into panels, arranging the panels for fabrication, and preparing visual documentation for installation.

The goal is to make the transition from a 3D design model to fabrication-ready outputs more manageable.

## Why ClimbFlow?

In climbing wall design, panelization involves more than dividing a surface. Panel boundaries, material dimensions, layout adjustments, and installation references all need to work together.

ClimbFlow was developed to explore how a repeatable, partially automated workflow can reduce repetitive operations while preserving opportunities for manual inspection and adjustment.

## Key Features

- **Panelization** — Divide a climbing wall surface into individual panels.
- **Layout generation** — Arrange panel outlines within standard sheet boundaries.
- **Manual adjustment** — Review generated layouts and adjust panel placement when needed.
- **DXF export** — Export 2D panel layouts in DXF format for downstream fabrication workflows, including laser cutting.
- **3D installation guide** — Provide a numbered 3D diagram to help installers identify and assemble individual panels.

## Workflow

1. **Prepare** — Start with a climbing wall model in Rhino 8.
2. **Generate** — Create panel geometry and an initial sheet layout.
3. **Review** — Inspect the results and manually adjust the layout or regenerate it when necessary.
4. **Export** — Produce DXF files and a numbered 3D installation reference.

The workflow combines automation with human review rather than relying entirely on one-click generation.

## Outputs

- **DXF files** for 2D panel fabrication workflows.
- **Numbered 3D installation diagrams** for on-site identification and assembly.

## Environment

- Rhino 8
- Windows

## Project Status

ClimbFlow is currently in its beta stage. The product interface and core workflow have been developed, and the project is moving toward broader user testing.

A public download page and user feedback channel are being prepared.

## Project Scope

This repository presents the project, its workflow, and supporting documentation. It does not include the plugin's implementation source code.

More screenshots, installation instructions, and usage documentation will be added as the project progresses.
