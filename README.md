# page-margin-boxes

Spec: https://www.w3.org/TR/css-page-3/#margin-boxes

Page margin boxes can be used by authors to define content on the outside of the page area, i.e. in the margin area.

See the figure at https://www.w3.org/TR/css-page-3/#page-model

![](https://www.w3.org/TR/css-page-3/images/PageBox.png)

The most interesting use case for this is for authors to specify their own headers and footers, including page numbering; see https://www.w3.org/TR/css-page-3/#page-based-counters

Currently, no web browser is known to support this, but it is supported by the Prince XML PDF generator.
