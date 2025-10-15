---
icon: material/svg
---

# SVG

The `DaxLib.SVG.SVG` function wraps your SVG content in a valid SVG container for use in Power BI visuals. All `DaxLib.SVG.Element.*` and `DaxLib.SVG.Compound.*` functions should be wrapped in this function to ensure correct metadata and rendering.

```dax
	DaxLib.SVG.SVG(
		"100",
		"100",
		"viewBox='0 0 100 100' ",
		DaxLib.SVG.Element.Circle("50", "50", "40", "fill:blue;", BLANK(), BLANK()),
		1
	)
```