# Badge

A set of badge/label components built with vanilla HTML and CSS.

## Overview

This project implements a small badge component system with multiple
sizes and color variants, commonly used to display statuses, tags, or
counts in a UI.

## Features

- 3 sizes: `sm`, `md`, `lg`
- 5 color variants: `neutral`, `danger`, `warning`, `success`, `brand`
- Pill-shaped badges with subtle border and background colors
- BEM-style class naming (`badge`, `badge--size-*`, `badge--color-*`)
- Custom typography via the Noto Sans Google Font

## Usage

Combine a size modifier and a color modifier on the base `.badge` class:

```html
<span class="badge badge--size-md badge--color-success">Label</span>
```

| Modifier            | Options                                             |
| -------------------- | ---------------------------------------------------- |
| `badge--size-*`      | `sm`, `md`, `lg`                                     |
| `badge--color-*`     | `neutral`, `danger`, `warning`, `success`, `brand`    |

## Tech stack

- HTML5
- CSS3

## Running locally

Open `index.html` directly in a browser, or serve the folder with any
static file server, e.g.:

```bash
npx serve .
```
