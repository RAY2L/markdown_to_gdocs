# Markdown Meeting Notes to Google Docs Converter

## Description
Convert markdown-formatted meeting notes into a Google Doc. This notebook automatically transforms structured markdown text into a properly formatted document with headings, nested bullet points, checkboxes, and styled mentions.

## Setup Instructions
1. Open the notebook in Google Colab
2. Make sure you're signed into a Google account
3. No installation needed - everything runs in the browser

## Required Dependencies
All dependencies are included in the notebook:
- Google authentication libraries
- Google Docs API
- Standard Python libraries

## How to Run in Colab
1. Run all cells in the notebook (Runtime > Run all)
2. When prompted, authorize the application
3. A link to your generated Google Doc will appear in the output of the last cell

## Features
- Converts markdown headings to proper Google Docs heading styles
- Preserves nested bullet point hierarchy
- Transforms checkboxes to interactive Google Docs checkboxes
- Highlights @mentions in bold (can be swapped for another style)
- Places meeting footer in document footer
