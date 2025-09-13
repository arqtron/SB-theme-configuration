# SB-theme-configuration

This is a user-friendly web app for customizing and generating custom themes for Markdown files in Silver Bullet, supporting both light and dark modes. Users can edit theme variables such as colors, fonts, and syntax styles through an intuitive interface with a live preview.

Features:
- Initialization: Automatically sets up the preview, parses the default theme Markdown, initializes state (mode, variables, content), and updates controls and preview.
- User Interface: Includes a live preview section, controls for editing theme properties, and action buttons for loading custom files, downloading modified themes, resetting changes, and toggling between light and dark modes.
- Core Functions: Allows live editing of CSS theme variables, switching between light and dark modes, loading custom Markdown themes, and generating downloadable modified Markdown files with applied changes. (Note: This feature does not work yet.)
- Technical Details: Implements JavaScript for managing state, parsing Markdown and CSS variables, handling color conversions, and notifications. All HTML, CSS, and JS are contained in a single file for better portability.
