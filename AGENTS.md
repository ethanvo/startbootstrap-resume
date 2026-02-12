# AGENTS.md

## Build/Lint/Test Commands

### Build Commands

- `npm run build` - Builds the entire project (assets, HTML, JS, CSS into dist)
- `npm run build:assets` - Copies files from src/assets/ to dist
- `npm run build:pug` - Compiles Pug files in src/pug/ to HTML in dist
- `npm run build:scripts` - Copies src/js/scripts.js to dist
- `npm run build:scss` - Compiles SCSS files in src/scss/ to CSS in dist
- `npm run clean` - Deletes the dist directory to prepare for rebuilding

### Development Commands

- `npm start` - Runs the build, launches live preview in browser, and watches for changes
- `npm run start:debug` - Runs the project in debug mode

### Testing

- No specific test commands found in package.json
- This project is a static template without explicit test suite

## Code Style Guidelines

### General

- Uses 4-space indentation (per .editorconfig)
- UTF-8 encoding
- Final newlines and trailing whitespace trimmed (per .editorconfig)

### JavaScript

- Uses ES6+ syntax
- Follows standard JavaScript conventions
- Comments use `//` style
- No explicit linting configuration found
- All JavaScript is in a single file: src/js/scripts.js

### SCSS/CSS

- Uses SCSS with Bootstrap 5 framework
- Follows BEM-like naming conventions in component structure
- Imports variables first, then Bootstrap, then custom styles
- Modular structure with separate files for components, sections, and global styles

### HTML/Pug

- Uses Pug templating language
- Bootstrap 5 classes used throughout
- Semantic HTML structure
- Responsive design with Bootstrap grid system
- Follows existing template structure

### File Structure

- `src/` directory contains source files
- `dist/` directory contains built output
- `scripts/` directory contains build scripts
- Source files organized by type: js, scss, pug, assets

### Naming Conventions

- Component names in SCSS follow lowercase with hyphens (e.g., `sidenav.scss`)
- Class names in HTML use Bootstrap conventions with custom additions
- JavaScript variable names use camelCase
- File names are lowercase with hyphens

### Error Handling

- No explicit error handling patterns found in source code
- Relies on standard JavaScript error handling
- Bootstrap framework handles most UI interactions

### Code Organization

- JavaScript is organized in a single file with DOMContentLoaded event
- SCSS is organized into modular files following a component-based approach
- Pug files follow a structured layout with defined sections

## Cursor/Copilot Rules

No specific Cursor rules found in .cursor/rules/ or .cursorrules
No specific Copilot rules found in .github/copilot-instructions.md
