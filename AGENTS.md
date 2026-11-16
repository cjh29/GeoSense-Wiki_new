# AGENTS.md

## Project
- Project name: GeoSense Wiki
- Subtitle: GIS & Remote Sensing Quick Reference
- Purpose: 建立一個以 GIS / Remote Sensing 為主題的科技感快速查詢型 Wiki。
- Target users: GIS / Remote Sensing students.
- Positioning: 工具參考型、快速查詢，不是完整課程、論文資料庫或即時資料平台。

## Website
- Main page: `index.html`
- Architecture: Single Page.
- Visual style: dark technology style with blue/cyan accents.
- Keep the interface clean and restrained; avoid unnecessary animations.
- The website should remain usable on desktop and smaller screens.
- Search should remain simple client-side text matching. Do not introduce complex search infrastructure.

## Language
- Chinese is the primary language.
- Keep important English technical terminology.
- Preferred format:
  `中文名稱（English Name, Acronym）`
- Do not translate technical acronyms away.

## Content Categories
1. Satellites
2. Products
3. Concepts
4. GIS Tools

## Current Topics
### Satellites
- Landsat
- Sentinel-2
- MODIS

### Products
- MCD64A1 Burned Area
- Sentinel-2 L2A
- Landsat Level-2

### Concepts
- NDVI
- NDWI
- LST

### GIS Tools
- QGIS

## Content Templates
Use the corresponding template in `templates/` before adding or rewriting a topic.

### Satellite
- Title
- English Name
- Overview
- Key Information
- Applications
- Related Products
- Related Topics

### Product
- Title
- English Name
- Overview
- Data/Product Information
- Applications
- Related Satellite
- Related Concepts

### Concept
- Title
- English Name
- Definition
- Formula/Key Information
- Interpretation
- Applications
- Related Data
- Related Topics

### GIS Tool
- Title
- English Name
- Overview
- Main Functions
- GIS Applications
- Remote Sensing Applications
- Related Topics

## File Naming
- Use lowercase.
- Use kebab-case.
- Keep files in the correct category folder.
- Do not create duplicate files for the same topic.

## AI Modification Rules
Before modifying the project:
1. Read this `AGENTS.md`.
2. Identify the relevant category.
3. Select the corresponding template.
4. Modify only the files necessary for the requested change.
5. Preserve the existing visual style and information architecture.
6. Check internal topic names and links after changes.

## Adding Knowledge
When adding a topic:
1. Confirm that it belongs to one of the four categories.
2. Create a Markdown file in the correct `content/` folder.
3. Follow the matching template.
4. Use Chinese as the main language and retain English technical terminology.
5. Add the topic to the website navigation/topic data when required.
6. Add useful related-topic references without duplicating existing content.

## Modifying the Website
- `index.html` is the public website entry point.
- Keep the site single-page unless the project owner explicitly changes this rule.
- Do not introduce a backend, database, login system, real-time API, or unnecessary package/build system.
- Do not arbitrarily change the four-category structure.
- Do not change the theme without explicit approval.
- Keep simple search behavior.

## Do Not
- Do not delete existing knowledge without explicit approval.
- Do not modify unrelated files.
- Do not introduce unnecessary dependencies.
- Do not create duplicate topics.
- Do not turn the project into a real-time satellite-data platform.
- Do not add an AI chatbot unless explicitly requested.
- Do not add complex GIS online analysis unless explicitly requested.

## Acceptance Criteria
A completed change should:
- Follow this file's rules.
- Keep the project structure clear.
- Keep Markdown content consistent with its template.
- Keep the website functional.
- Avoid broken navigation or obvious JavaScript errors.
- Preserve the project's purpose and visual identity.

## Project Workflow
AGENTS.md → Templates → Content → index.html → Test → GitHub Pages
