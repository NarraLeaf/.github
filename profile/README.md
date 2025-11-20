<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-transparent.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-light.png">
  <img alt="narraleaf banner" src="https://raw.githubusercontent.com/NarraLeaf/.github/refs/heads/master/doc/banner-md-light.png">
</picture>

<h1 align="center">NarraLeaf</h1>

<h4 align="center">A new definition of Visual Novel. </h3>

<p align="center">English | <a href="./README-zh.md">简体中文</a></p>

## What are we?

We are a team dedicated to building a lighter, faster, and more developer-friendly visual novel engine.

NarraLeaf is a lightweight, React-based visual novel engine built for speed and developer control. Build and package cross-platform VNs with minimal code and maximum flexibility.

## Why us?

- ⚡**Lighter** – A zero-rendering engine with minimal overhead, optimized to run smoothly on most low-end devices.
- 🔧**Faster** - Customizable apps and built-in automation like CI and linting help you build faster with less hassle.
- 💻**More Developer Friendly** - Standardized front-end development experience with strict typing and no language dependencies

### 🔍 Visual Novel Engine Comparison – Pros & Cons

This comparison highlights key differences to help developers choose based on their specific project needs.

| Feature / Tool                          | **NarraLeaf (React/TypeScript)**                                | **Ren’Py (Python)**                                           | **TyranoBuilder (GUI)**                                        |
|----------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|
| **Lightweight Performance**          | ✅ Zero-render engine, optimized for low-end devices             | ⚠️ Moderate runtime footprint                                  | ⚠️ Heavier rendering, may affect performance on low-end devices |
| **Modern Web Tech Support**          | ✅ Uses React + TypeScript stack                                 | ❌ Python-based, limited web stack integration                  | ⚠️ Partial JavaScript support                                   |
| **Component Architecture**           | ✅ Modular architecture with reusable React components           | ❌ Linear, script-based structure                               | ❌ Limited customization within visual editor                   |
| **Cross-Platform Build**             | ✅ Web-ready and desktop builds via Electron                     | ✅ Supports multiple platforms                                  | ✅ Supports multiple platforms                                  |
| **Technical Skill Requirement**      | ✅ TypeScript or zero-code, greater freedom      | ✅ Beginner-friendly scripting with Python                      | ✅ No coding required, drag-and-drop interface                  |
| **Scripting Language**               | ✅ In Development (NarraLang scripting language)         | ✅ Stable scripting with Ren'Py Script (Python-based)           | ✅ Simple visual scripting interface                            |
| **Extendability**                    | ✅ Can leverage full React ecosystem                             | ⚠️ Extendable via Python modules                               | ⚠️ Limited options beyond built-in tools                        |
| **Localization / Multi-language**    | 🟡 Manual setup or community-based plugins in progress           | ✅ Built-in multi-language and font support                     | ✅ Built-in language switching                                  |
| **GUI Editor / Visual Tooling**      | ✅ All-in-One IDE             | ✅ Basic GUI for script management                              | ✅ Full-featured visual editor for scenes and dialogs           |
| **UI Themes / Visual Templates**     | ✅ In Development (NarraUI Library)         | ⚠️ Customizable via ATL scripting and config files             | ✅ Built-in visual themes and UI templates                      |

## Solutions

### [NarraLeaf](https://github.com/NarraLeaf/NarraLeaf) – Complete desktop solution

> **Less Code Required**  

Create, build and package your desktop visual novel.  
Focused on cross-platform desktop applications, with built-in NarraLeaf-React, local save support, and page-based routing. Supports packaging and development server via command-line tools.

- Desktop (Electron) development
- Out-of-the-box development server and packaging tools
- Local storage support, page-level routing control
- Built-in front-end view engine (NarraLeaf-React)

### [NarraLeaf-React](https://github.com/NarraLeaf/narraleaf-react) - Embedded VN player solution

> **Maximum customizability**

A lightweight front-end visual novel player built for React.  
Focused on stage performance, with everything built-in: images, dialogs, and extensible React components.

- Suitable for web or custom front-end
- Complete stage management system (Stage Manager)
- React component architecture, support for extension and customization
- Can be independently integrated into any React application

## Projects

### react.narraleaf.com

Documentation and demo site for NarraLeaf-React.

> [react.narraleaf.com](https://react.narraleaf.com)

### NarraUI (in progress)

Quickly customize all the visual novel components you need using a plugin of NarraLeaf-React.

> [NarraUI](https://github.com/NarraLeaf/NarraUI)

### NarraLang (planning)

Eliminate code with simpler language

### NarraLeaf Studio (in progress)

Zero-code, All-in-One Visual Novel IDE

### NarraLeaf.com (planning)

Documentation for NarraLeaf. 

### CharPack (in progress)

Image compression tool for optimizing character assets
