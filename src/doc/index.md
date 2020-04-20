## Introduction

Generates a pie chart from a dataset

**NOTE:**
This WireCloud operator is based on pie-chart-generator-operator of [agile-dashboards](https://github.com/Wirecloud/agile-dashboards)
created by CoNWeT Lab., Universidad Politecnica de Madrid and Future Internet Consulting and Development Solutions S.L..

## Settings

- `Chart Title`: The title for the chart.

## Wiring

### Input Endpoints

- `Number Data Serie`: A data series made of numeric values. Each number represents a pie)
- `Label Data Serie`: A data series made of labels. Each label represents a pie, counts repetitions to get their size.

### Output Endpoints

- `Chart Data Model`: The chart data model to be passed to the Highcharts widget.

## Usage

Plug in one of the inputs (`Label Data Serie` takes preference) and plug the output to the Highcharts widget.

## Reference

- [FIWARE Mashup](https://mashup.lab.fiware.org/)
