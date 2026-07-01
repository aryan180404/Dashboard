# Sales & Customer Dashboards

This repository contains a packaged Tableau workbook: `Sales & Customer Dashboards.twbx`. The workbook includes dashboards and packaged data (Hyper file) used to analyze sales and customer metrics.

> File: Sales & Customer Dashboards.twbx  
> Repo: aryan180404/Dashboard  
> Commit OID (reference): 06d79db979b95dfc047a00e4960937cff630da41

---

## Overview

`Sales & Customer Dashboards.twbx` is a Tableau Packaged Workbook (.twbx). A .twbx bundles the Tableau workbook (.twb) together with its data sources (for example `.hyper` files), images, and custom shapes into a single ZIP-like package so the workbook can be opened and viewed even when the original data connection is not available.

Typical contents:
- Tableau workbook (.twb) with dashboard definitions and visualizations
- Data folder (contains a `.hyper` file or other embedded sources)
- Supporting assets (images, custom shapes, etc.)

This file enables offline sharing and reviewing of the dashboards.

---

## How to open and view

Recommended tools:
- Tableau Desktop (full authoring & editing)
- Tableau Reader (free — view-only)
- Tableau Public (if you intend to publish publicly and there is no confidential data)

To open:
1. Install Tableau Desktop or Tableau Reader.
2. Double-click the `.twbx` file or open it from within Tableau via File → Open.

If you do not have Tableau Desktop/Reader, see the extraction + alternative instructions below.

---

## Extracting data from the .twbx (advanced / developers)

A `.twbx` is a ZIP archive. You can extract the embedded data files (for example, the `.hyper` database) using standard ZIP tools.

On macOS/Linux/Windows (with unzip available):
