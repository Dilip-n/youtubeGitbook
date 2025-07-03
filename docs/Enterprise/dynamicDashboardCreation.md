# Dynamic Dashboard and User-Level Dashboard Configuration

![Dynamic Dashboard Configuration](../assets/Dashboard%20configuration.png)

## Overview

This documentation explains how to configure dynamic dashboards tailored for different user types. Dashboards are structured to allow flexibility in layout, KPI selection, and presentation — enabling administrators to define multiple user-specific views.

## 1. User Type Selection

When starting the configuration, the user will first be prompted to **select the user type** for which the dashboard is being configured. The available roles include:

- **Admin**
- **Power User**
- **Manager**
- **Monitor**
- *(You can also add more roles based on your system configuration)*

This selection ensures that dashboards can be customized based on role-specific needs and visibility levels.

## 2. Layout Configuration: Rows and Columns

After selecting the user type, the user can **configure the layout** of the dashboard.

- You can add **multiple rows** to the dashboard.
- Each row can contain **multiple columns (cells)**.
- The number of columns in each row is flexible, and you can customize it as per screen size or user requirement.

### Example:

- **Row 1**: 3 columns (KPI1 | KPI2 | KPI3)
- **Row 2**: 2 columns (KPI4 | KPI5)

## 3. KPI/Tile Configuration in Each Cell

For **each cell in the layout**, the user can configure the following details:

| Configuration Option | Description |
|----------------------|-------------|
| **Size of the KPI/Tile** | Define the size of the tile (e.g., small, medium, large). This could correspond to screen grid units like 1x1, 2x2, etc. |
| **KPI/Tile Name** | Select the KPI or widget from a predefined list. This could be energy consumption, uptime, alerts, cost metrics, etc. |
| **KPI/Tile Title** | Define the display title that will appear on the tile. Example: "Today's Energy Usage" |
| **KPI/Tile Info** | Optionally add an info tooltip or short description that helps users understand the purpose or source of the KPI. |

Each of these settings allows the user to fully personalize the dashboard based on what’s most important for their role.

## 4. Final Review and Save

Once all rows, columns, and KPIs are configured:

1. Preview the dashboard layout in a live or mock preview window.
2. Save the configuration. This setup will now be visible to the selected user type.


![User leavel configuration](../assets/user%20leavel%20configration.png)

## Summary

With this setup, you can create:
- **Highly customized dashboards** per user type.
- **Modular layouts** with multiple rows and cells.
- **Fine-tuned visualizations** with informative KPIs.

This feature helps enterprises and organizations deliver **role**