
Charts for Go
=============

Basic charts in go.

This package focuses more on autoscaling, error bars,
and logarithmic plots than on beautifull or marketing
ready charts.

## Examples

![Some nice charts](https://github.com/wzshiming/chart/raw/master/example/bestof.png)


## Chart Types

The following chart types are implemented:
* Strip Charts
* Scatter / Function-Plot Charts
* Histograms
* Bar and Categorical Bar Charts
* Pie/Ring Charts
* Boxplots

## Some Features
* Axis can be linear, logarithmical, categorical or time/date axis.
* Autoscaling with lots of options
* Fine control of tics and labels

## Output / Graphic Formats

Package chart itself provideds the charts/plots itself, the charts/plots
can be output to different graphic drivers.  Currently
* txtg: ASCII art charts
* svgg: scalable vector graphics (via github.com/ajstarks/svgo), and
* imgg: Go image.RGBA (via code.google.com/p/draw2d/draw2d/ and code.google.com/p/freetype-go) 
are implemented.

For a quick overview save as xbestof.{png,svg,txt} run
```bash
  $ example/example -best
```
A fuller overview can be generated by
```bash
  $ example/example -All
```

## Quirks
* Style handling (especialy colour) is a bit of a mess .
* Text based charts are cute. But the general graphics would be much easier without.
* Time handling code dates back to pre Go1, it should be reworked.


