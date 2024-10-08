﻿# Minimalist Soft Black Theme for Spicetify

## Description

This is an experimental and trial theme for [Spicetify](https://github.com/spicetify/spicetify-cli), designed with a minimalist. Key features include:

- **Soft Black Palette:** Utilizes soft black colors to create a stylish minimalist interface.
- **Transparency and Blur:** Adds transparent elements and blur effects for a clean and sleek look.
- **Rounded Corners:** Most interface elements feature smooth rounded corners.
- **Minimalist Text:** Simplified textual information, especially in the sidebar, which expands on hover.

## Installation

### 1. Clone the Repository

Make sure you have Git installed, then run the following command:

```bash
git clone --depth=1 https://github.com/yourusername/your-repo-name.git
```

### 2. Move Theme Files

Copy the files into your current Spicetify themes directory:

**Linux / MacOS:**
```bash
cd your-repo-name
cp -r * ~/.config/spicetify/Themes
```

**Windows:**
```bash
cd your-repo-name
cp * "$(spicetify -c | Split-Path)\Themes\" -Recurse
```

### 3. Apply the Theme

Choose the theme to apply by running:

```bash
spicetify config current_theme YourThemeName
```

If your theme has multiple color schemes, you can switch between them with:

```bash
spicetify config color_scheme SCHEME_NAME
```

### 4. Update Configuration

After making changes, apply the new configuration:

```bash
spicetify apply
```

## Notes

- This theme is in an experimental and testing phase. Some elements may change in the future.
- This theme requires the latest version of Spotify and Spicetify.
- To install Dribbblish and Turntable themes, follow the instructions in their respective README files.
- The ad-blocked version of Spotify is not supported.

## Screenshots

_Screenshots showcasing the theme in action:_

(Add screenshots of the interface here.)![alt text](image.png)
