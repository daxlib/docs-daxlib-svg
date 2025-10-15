
# DaxLib.SVG

DaxLib.SVG is a DAX User-Defined Functions (UDF) library designed to make creating SVG visuals in Power BI easier.

[![Download From DaxLib](https://img.shields.io/badge/Download%20from%20DaxLib-009688?style=for-the-badge&logo=cloudsmith&logoColor=white)](https://daxlib.org/package/daxlib.svg/)
[![Download Example PBIP](https://img.shields.io/badge/Download%20Example%20PBIP-607D8B?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)](https://github.com/daxlib/docs-daxlib-svg/tree/main/PowerBI)

## Getting Started

1. Download the library from [DaxLib](https://daxlib.org/package/DaxLib.SVG/)
2. Install using TMDL view
3. Start using the functions in your measures
   
For detailed examples, check out our [example PBIP file](https://github.com/daxlib/docs-daxlib-svg/tree/main/assets/PBIP).

---

## Function Categories

| Category | Description |
|---|---|
| **SVG Wrapper** | Wraps one or more `Elements`, `Defs`, `Compounds`, applying required metadata and `<SVG>` tags |
| **Elements** | SVG primitives (i.e. `<Rect>`, `<Circle>`, `<line>`) |
| **Compounds** | Complex components (i.e. boxplot, violin) made from `Elements` |
| **Defs** | Define reusable SVG elements (i.e. `<linearGradient>`, `<clipPath>`, and shapes) |
| **Attributes** | Create Attributes (i.e. fill, stroke, opacity) string that can be applied to `Elements` and `Defs` |
| **Transforms** | Create Transform strings |
| **Scales** | Mapping values between scales |
| **Colors** | Themes and functions for colour manipulation |

---

Full documentation is available at our [GitHub Pages site](https://daxlib.github.io/docs-daxlib-svg/).

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)
