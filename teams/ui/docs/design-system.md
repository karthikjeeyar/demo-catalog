# MUI Usage Standards

To keep our RHDH plugins looking uniform, we follow these MUI implementation guidelines:

### 1. Theme Provider
We wrap our plugins in the standard RHDH theme provider to ensure that MUI components inherit the correct primary/secondary colors and spacing.

### 2. Common Components
Always use our pre-styled MUI wrappers for:
* **Data Grids:** For large lists of services.
* **Modals:** For confirmation actions in Scaffolder.
* **Status Chips:** For indicating build/deploy health.

### 3. Responsive Breakpoints
We design for the "RHDH Layout," which includes a persistent sidebar. Always test your plugin UI at **1280px** and **1920px**.