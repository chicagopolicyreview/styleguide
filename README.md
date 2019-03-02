# CPR Data Visualization Style Guide

Design specifications for CPR data visualization products and related code

TODO:

- [ ] Insert visual example
- [ ] Secondary colors for cateogorical data
- [ ] Gradient color palette - define endpoints
- [ ] Submission guidelines for code

# Sizing 

| Element     | Description                             | Notes
| ---         | ---                                     | ---
| Width       | Minimum 600px, max display width 800px  | Height determined by 4:3 aspect ratio
| Margins     | Min 5px around all elements             | Variable by location
| CPR Logo    | Top right, 100px, full opacity          | Consider right-aligning logo text
| Gridlines   | 1px, #DDDDDD, major ticks only          | Keep to only one axis unless strictly necessary (e.g. with scatterplots)


# Typography

Major text elements that reader should see first, by order of importance, are: title > axes titles > legend titles > subtitle > all other text. Importance here is signalled by size and color, such that less-important information doesn't clutter up the immediate visual impact of the chart. 

In other words, the reader should be able to get the following four questions with minimal effort:
  
  1.  What is the main takeaway from this chart?
  2.  What data am I looking at?
  3.  What do the primary visual encodings mean?
  4.  What's the context for this data?

Element       | Font          | Size  | Face    | Color   | Case
---           | ---           | ---   | ---     | ---     | ---
Title (serif) | Merriweather  | 18px  | plain   | #FFFFFF | Title Case
Title (sans)  | Open Sans     | 18px  | plain   | #FFFFFF | Title Case
Subtitle      | Open Sans     | 12px  | plain   | #3F3F3F | Sentence case
Axis title    | Open Sans     | 10px  | **bold**  | #FFFFFF | UPPER CASE
Axis text     | Open Sans     | 10px  | plain   | #3F3F3F | -
Legend title  | Open Sans     | 10px  | **bold**    | #3F3F3F | Title Case
Legend text   | Open Sans     | 10px  | plain   | #3F3F3F | Title Case
Annotations   | Open Sans     | 8px   | _italic_  | #FFFFFF | Sentence case
Caption       | Open Sans     | 8px   | _italic_  | #FFFFFF | Title Case


# Color Palettes

## Theme Colors

Color         | Hex       | RGB               | CMYK  
---           | ---       | ---               | ---
Maroon        | #661B16   | rgb(102,27,22)    | CMYK(0.0000,0.7353,0.7843,0.6000)
Light Grey    | #DDDDDD   | rgb(221,221,221)  | CMYK(0.0000,0.0000,0.0000,0.1333)
Charcoal Grey | #3F3F3F   | rgb(63,63,63)     | CMYK(0.0000,0.0000,0.0000,0.7529)

## Secondary Colors

Red           | #B21F15
---           | ---


## Gradients and Choropleths 

TBD


# Specifying Themes in R Code

Submission guidelines - your theme should be easy to replace with CPR's.

Theme in R Notebook or specified in different file?
