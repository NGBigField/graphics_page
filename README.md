# Interactive Plot Gallery

A collection of standalone Plotly HTML exports.  Each file is a fully self-contained interactive plot that you can open in any browser.

## Contents

| File                | Description                                    |
|---------------------|------------------------------------------------|
| `index.html`        | Landing page with links to all plots           |
| `tetrahedron.html`  | 3D Tetrahedron with arrow axes (from Q1)       |

## How to new Plots

1. In your Python script, export the figure:
   ```python
   fig.write_html("newplot.html", full_html=True, include_plotlyjs="cdn")
