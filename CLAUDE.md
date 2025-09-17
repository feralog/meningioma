# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an academic medical presentation project focused on a case study of a giant meningioma of the left hemisphere. The project contains materials for creating an interactive HTML presentation about a neurosurgical case published in Frontiers in Oncology (December 2024).

## Key Files and Structure

### Medical Content
- **`document.md`** - Complete case report content (30k+ words) including patient details, surgical technique, and medical findings
- **`slides.md`** - Structured presentation slides content with 21 slides covering the case from introduction to conclusions
- **`roteiro.md`** - Detailed presentation script with timing and speaking notes for each slide

### Templates and Development
- **`template.html`** - HTML template for creating interactive slide presentations with responsive design
- **`template-prompt.md`** - Template prompt for generating customized HTML presentations
- **`prompt.md`** - Specific prompt for this meningioma presentation with detailed specifications

### Medical Images
- **`figures/`** directory contains:
  - `figure1.jpeg` - MRI from 2021 (pre-tumor)
  - `figure2.png` - Pre and post-operative MRI comparison
  - `figure3.png` - Surgical visualization and histology
  - `figure4.jpeg` - Patient symptom timeline

## Medical Context

This case study involves:
- A 77-year-old female patient with a rapidly growing meningioma (0 to 13cm in 3 years)
- Use of sodium fluorescein-guided surgery for tumor resection
- WHO Grade II atypical meningioma
- Complete surgical resection with significant neurological recovery

The content is suitable for medical education, neurosurgery training, and academic presentations.

## Development Workflow

This is a static content project with no build system. The typical workflow involves:

1. **Content Creation**: Medical content is already prepared in markdown files
2. **Template Customization**: Use `template.html` as base and customize with content from `slides.md`
3. **Presentation Generation**: Follow specifications in `prompt.md` to create interactive HTML presentations
4. **Manual Process**: No automated build tools - all content editing and HTML generation is manual

## Working with Templates

When creating presentations:
- Use the color scheme specified in `prompt.md`: #4a90e2 (primary) and #7b68ee (secondary)
- Follow the 21-slide structure defined in `slides.md`
- Integrate medical images from `figures/` directory appropriately
- Maintain responsive design for both desktop and mobile viewing

## Content Guidelines

- All medical content is factual and based on published research
- Images should be properly attributed to the original case study
- Maintain professional medical presentation standards
- Respect patient privacy (case is already published and anonymized)