# Project Screenshots

This folder contains screenshots for the projects showcased in the portfolio.

## Folder Structure

```
screenshots/
├── efims/
│   ├── login-dashboard.jpg
│   ├── financial-dashboard.jpg
│   ├── budget-management.jpg
│   └── reports-analytics.jpg
├── e-hris/
│   ├── employee-dashboard.jpg
│   ├── attendance-system.jpg
│   ├── payroll-management.jpg
│   └── hr-reports.jpg
└── design-portfolio/
    ├── brand-identity.jpg
    ├── print-materials.jpg
    ├── digital-assets.jpg
    └── ui-ux-design.jpg
```

## How to Add Screenshots

1. **Create project folders**: Create a folder for each project (e.g., `efims/`, `e-hris/`, `design-portfolio/`)

2. **Add your screenshots**: Place your screenshot images in the appropriate project folder

3. **Update the projects.html file**: Replace the placeholder divs with actual image tags

### Example: Adding a Screenshot

Replace this placeholder in `projects.html`:
```html
<div class="screenshot-placeholder">
    <div style="text-align: center;">
        <i class="fas fa-image"></i>
        <div>Login Dashboard</div>
    </div>
</div>
```

With an actual image:
```html
<img src="screenshots/efims/login-dashboard.jpg" alt="e-FIMS Login Dashboard" style="width: 100%; height: 250px; object-fit: cover;">
```

## Image Guidelines

- **Format**: Use JPG or PNG format
- **Size**: Recommended 800x600px or larger
- **Quality**: High quality, clear screenshots
- **File naming**: Use descriptive names with hyphens (e.g., `login-dashboard.jpg`)

## Recommended Screenshots for Each Project

### e-FIMS System
- Login Dashboard
- Financial Dashboard
- Budget Management Interface
- Reports & Analytics Page

### e-HRIS System
- Employee Dashboard
- Attendance System
- Payroll Management
- HR Reports

### Design Portfolio
- Brand Identity Examples
- Print Materials
- Digital Assets
- UI/UX Designs

## Tips for Good Screenshots

1. **Clean interface**: Make sure the interface is clean and professional
2. **Good lighting**: Ensure the screenshot is well-lit and clear
3. **Relevant content**: Show meaningful data/content in the screenshots
4. **Consistent styling**: Use similar styling across all screenshots
5. **Mobile responsive**: Consider taking screenshots of mobile versions too

## Updating the Gallery

After adding screenshots, update the `projects.html` file to replace all placeholder divs with actual image tags. The images will automatically be responsive and maintain the same styling as the placeholders.
