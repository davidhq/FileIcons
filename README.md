# FileIcons
Colored file icons for Sublime Text.

Adds specific, colored icons for most file types for the sidebar in Sublime Text 3. Supports both the Default and Adaptive themes.

## Customize

The following changes are made to Adaptive/Default.sublime-theme. You can override them by creating a theme file with the same name in your Packages/User directory.

```json
[
  {
    "class": "icon_file_type",
    "layer0.tint": [255, 255, 255],
    "layer0.opacity": 0.75,
    "content_margin": [8, 8]
  },
  {
    "class": "icon_file_type",
    "parents": [{"class": "tree_row", "attributes": ["hover"]}],
    "layer0.opacity": 0.5
  },
  {
    "class": "icon_file_type",
    "parents": [{"class": "tree_row", "attributes": ["selected"]}],
    "layer0.opacity": 1.0
  }
]
```
