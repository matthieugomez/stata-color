# Stata-colorbrewer


- This function returns colors for a given palette and number of colors

```
colorbrewer Blues, n(4)
```




# Palettes

The palettes can be found on (http://colorbrewer2.org/)[colorbrewer 2.0].
There are 3 types of palettes, sequential, diverging, and qualitative.

- Sequential palettes are suited to ordered data that progress from low to high. Lightness steps
dominate the look of these schemes, with light colors for low data values to dark colors for high
data values. All the sequential palettes are available in variations from 3 different values up to 9 different values.

The sequential palettes names are
Blues BuGn BuPu GnBu Greens Greys Oranges OrRd PuBu PuBuGn PuRd Purples RdPu Reds
YlGn YlGnBu YlOrBr YlOrRd

- Diverging palettes put equal emphasis on mid-range critical values and extremes at both ends
of the data range. The critical class or break in the middle of the legend is emphasized with light
colors and low and high extremes are emphasized with dark colors that have contrasting hues. All the diverging palettes are available in variations from 3 different values up to 11 different values.


The diverging palettes are
BrBG PiYG PRGn PuOr RdBu RdGy RdYlBu RdYlGn Spectral

- Qualitative palettes do not imply magnitude differences between legend classes, and hues are
used to create the primary visual differences between classes. Qualitative schemes are best suited
to representing nominal or categorical data. The qualitative palettes (with their associated maximum number of colors) is
Accent 8
Dark2 8
Paired 12
Pastel1 9
Pastel2 8
Set1 9
Set2 8
Set3 12



ColorBrewer is Copyright (c) 2002 Cynthia Brewer, Mark Harrower, and The Pennsylvania State
University. All rights reserved.