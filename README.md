# Kingly Paragraph Gallery

Installs a responsive and accessible gallery paragraph with several curated grid
layout options.

## Overview

This recipe creates a new paragraph type named "Kingly Gallery". This paragraph
allows content editors to create visually engaging image galleries by simply
adding media items and selecting a predefined layout.

## Features

* **Selectable Grid Layouts**: Editors can choose from several responsive grid
  patterns:
* Uniform 2, 3, or 4-column grids.
* A "Featured Top" layout (1 large image over 3 smaller ones).
* A "Featured Left" layout (1 tall image beside 4 smaller ones).
* **Optimized Images**: A new responsive image style, `gallery_responsive`, is
  created specifically for this component to ensure images are appropriately
  sized for different breakpoints and layouts.
* **Component-Driven**: The frontend rendering is powered by
  the `kingly_minimal:gallery` Single Directory Component (SDC), which uses
  modern CSS Grid for robust, accessible, and responsive layouts.
* **Media Reusability**: Leverages the existing media types provided by
  the `kingly_paragraph_media` recipe.

## Dependencies

This recipe requires the following:

* `kingly_page` recipe (for content placement).
* `kingly_paragraph_media` recipe (for base media types and fields).
* `kingly_minimal` theme (for the required `gallery` SDC).
