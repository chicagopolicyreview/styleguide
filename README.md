# CPR Data Viz Style Guide

Design specifications for CPR data visualization products and related code

TODO: insert visual example

# Sizing 

| Element     | Description                             | Notes
| ---         | ---                                     | ---
| Width       | Minimum 600px, max display width 800px  | Height determined by 4:3 aspect ratio
| Margins     | Min 5px around all elements             | Variable by location
| CPR Logo    | Top right, 100px, full opacity          | Consider right-aligning logo text


# Typography

Major text elements that reader should see first, by order of importance, are: title > axes titles > legend titles > subtitle > all other text. Importance here is signalled by size and color, such that less-important information doesn't clutter up the immediate visual impact of the chart. 
  
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
<span style="color:#661B16;>**Maroon**</span>        | #661B16   | rgb(102,27,22)    | tbd
Chargoal Grey | #DDDDDD   | rgb(221,221,221)  | tbd

## Secondary Colors

TBD

## Gradients and Choropleths 

TBD