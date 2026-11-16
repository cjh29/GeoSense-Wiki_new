# GeoSense Wiki

**GIS & Remote Sensing Quick Reference**

GeoSense Wiki 是一個以 **GIS / Remote Sensing** 為主題的科技感快速查詢型 Wiki，主要提供學生快速查找衛星、資料產品、遙測概念與 GIS 工具的基本資訊。

## Project Purpose

本專案的重點不只是建立一個網頁，而是建立一個具有明確規則的專案環境，讓 AI 能依照 `AGENTS.md` 持續新增、修改與維護內容。

## Categories

- **Satellites** — Landsat, Sentinel-2, MODIS
- **Products** — MCD64A1 Burned Area, Sentinel-2 L2A, Landsat Level-2
- **Concepts** — NDVI, NDWI, LST
- **GIS Tools** — QGIS

## Project Structure

```text
GeoSense-Wiki/
├── AGENTS.md
├── README.md
├── index.html
├── content/
│   ├── satellites/
│   ├── products/
│   ├── concepts/
│   └── gis-tools/
├── templates/
└── assets/
    ├── images/
    └── icons/
```

## Website

The project uses a **single-page website**.

- Dark technology-style interface
- Blue/cyan visual accents
- Simple topic search
- Topic cards and same-page detail view
- Related-topic navigation

## AI Development Rules

`AGENTS.md` is the project's main AI instruction file.

When AI modifies the project, it should:

1. Read `AGENTS.md`.
2. Identify the category and relevant template.
3. Add or modify the Markdown content.
4. Update the website when necessary.
5. Check navigation, formatting, and obvious errors.

## Scope

This project intentionally does not include:

- Backend or database
- User login
- Real-time satellite data
- Online GIS analysis
- Live APIs
- Complex search
- AI chatbot

## Local Preview

Open `index.html` in a browser to preview the website.

For the assignment, the final project can be published through GitHub Pages.
