# ScadaAdminWebJP User Guide

[Русский](../ru/README.md) · [Home](../README.md)

ScadaAdminWebJP is a browser-based project administrator for Rapid SCADA. Use it
to edit the configuration database and project files, configure an instance's
applications, and prepare configuration for transfer to a running system.

This guide covers the application itself. Protocol configuration and the
operation of individual drivers, plugins and specialized extensions are outside
its scope.

![ScadaAdminWebJP main window in English](assets/02-main-window.png)

## Contents

| Section | What you will learn |
|---|---|
| [Projects](projects.md) | Sign in, open or create a project, and make a backup. |
| [Workspace](workspace.md) | Use the toolbar, project tree, document tabs and save commands. |
| [Configuration database tables](tables.md) | Edit rows, filter data, update cells in bulk, validate, import and export. |
| [Editor settings](settings.md) | Choose the language, theme and tab behavior, and find other general settings. |
| [Deployment](deployment.md) | Select a connection profile and upload or download configuration. |
| [Help and troubleshooting](support.md) | Find support and resolve common difficulties. |

## First steps

1. Open the address of your ScadaAdminWebJP installation and sign in with username `admin` and password `scada`.
2. Click **Open project** and select the required project.
3. Check its name and path in the top bar.
4. In the tree, open **Configuration Database → Primary Tables → Devices**.
5. Inspect the table; use **Table search** to find a record.
6. After editing, click **Validate**, then **Save**.
7. Before uploading to an instance, save all changed tabs and check the
   [deployment profile](deployment.md).

**Next:** [Opening and creating projects](projects.md).
