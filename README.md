# Organic UI Framework

A custom CSS framework offering a hybrid approach (components + utilities). Built for 'organic' adaptability, it's designed for easy brand integration and streamlined UI creation, allowing you to efficiently mold components to fit your project's unique style.

## Description

A custom CSS framework offering a hybrid approach (components + utilities). Built for 'organic' adaptability, it's designed for easy brand integration and streamlined UI creation, allowing you to efficiently mould components to fit your project's unique style.

## Version

Current Version: **0.1.0 (Alpha)**

This project is currently in its early alpha stage. Features and structure may change significantly before a stable release.

## Installation

To use Organic UI Framework in your project, link the necessary CSS files in the `<head>` section of your HTML document.

### Example

```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta
			name="viewport"
			content="width=device-width, initial-scale=1"
		/>
		<title>My Project</title>
		<!-- Link to the core CSS files -->
		<link
			rel="stylesheet"
			href="path/to/Organic-UI-Framework/CSS/variables.css"
		/>
		<!-- ... other links -->
	</head>
	<body>
		<!-- Your HTML content here -->
	</body>
</html>
```

_Note: Adjust the `href` paths according to your project structure._

## Usage

Organic UI aims for flexibility by providing both pre-defined components (like cards, badges, navigation) and utility classes for fine-grained control over styling. You can use the components directly or combine them with utility classes to achieve custom designs efficiently.

Refer to the individual CSS files within the `CSS/` directory for available classes and component structures (documentation forthcoming).

## File Structure

css/
├── base/
│ ├── base.css # Basic HTML element styles
│ ├── reset.css # (Optional) CSS reset
│ └── typography.css # Default font settings, headings etc. (if not utilities)
│ └── code.css # Default code styling (if not component)
│ └── links.css # Default link styling (if not component)
│ └── highlight.css # Default highlight styling (if not utility)
├── components/
│ ├── badge.css
│ ├── card.css
│ ├── button.css # (Example)
│ ├── alert.css # (Example - from ui-feedback)
│ ├── icon.css # (If defining icon components)
│ └── ...
├── utilities/
│ ├── spacing.css # Margins, padding
│ ├── colors.css # Text, background colors (from text.css, background.css)
│ ├── borders.css
│ ├── effects.css # Shadows, etc.
│ ├── typography.css # Text alignment, size utilities (if not base)
│ ├── layout.css # Display, position, width (part of utility.css?)
│ ├── gradients.css
│ └── ...
├── structure/ # Or layout/
│ ├── header.css
│ ├── footer.css
│ ├── nav.css
│ ├── sidebar.css
│ └── grid.css # (If you have a layout grid system)
├── themes/ # (Optional - for different themes)
│ └── dark-theme.css
└── variables.css # Root variables (or variables/ folder)

_Note: This structure provides clearer separation based on the purpose of the CSS rules._

## Changelog(s)

This project follows Semantic Versioning (SemVer).

### Understanding SemVer

Versions are numbered MAJOR.MINOR.PATCH:

- **MAJOR** version changes indicate incompatible API changes.
- **MINOR** version changes add functionality in a backwards-compatible manner.
- **PATCH** version changes include backwards-compatible bug fixes.

#### Version History

- **v0.2.0 (Alpha)** - Revised the CSS file structure for better organisation.
- **v0.1.0 (Alpha)** - Initial release. Basic structure, core styles, and initial set of components/utilities.

## Licence

This project is licenced under the MIT Licence.

---

## Contributing

Contribution guidelines will be added in the future. For now, please report any issues or suggest features via the project's issue tracker (when available).
