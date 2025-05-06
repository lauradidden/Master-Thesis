# 📊 Interactive Process Visualization Dash App (Master Thesis) 

An interactive Dash app for comparing sequential query paths in event log data. It allows analysts to visualize query path trees and evaluate how differences in case behavior impact key process metrics.

## Features

- Side-by-side comparison of paths (analyst-defined vs. alternative)
- Variant tree visualization with Dash Cytoscape
- Toggle metrics: percentage of cases, average duration, average amount
- Visual distinction between paths using color-coded nodes and edges

## Install dependencies

```bash
pip install dash dash-cytoscape dash-bootstrap-components
