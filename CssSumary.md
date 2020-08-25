### CSS Color


# How to specify colors?
coloring provide my page with a live style so you can color your text.
there are three common ways in which you can indicate your choice of colors :

1. RGB values : These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
2. HEX codes : These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80
3. Color names : There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

Tag  | Exampel
---- | ----
color name | h1 { color: DarkCyan;}
hex code | h2 {color: #ee3e80;}
rgb value | p {color: rgb(100,100,90);}

# Background color?
By default, most browser windows have a white background,You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names , If you do not specify a background color, then the background is transparent. 

##Note 
We have also used the padding property to separate the text from the edges of the boxes, This makes it easier to read.


# Color terminology and contrast?
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
###### we have a three type f contrast
1. Low Contrast
2. High Contrast
3. Meduim Contrast

- Text is harder to read when there is low contrast between background and foreground colors.
- Text is easier to read when there is higher contrast between background and foreground colors.
- For long spans of text, reducing the contrast a little bit improves readability.


# Note
- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


[To check contrast there is a handy online tool at:]( www.snook.ca/technical/colour_contrast/colour.html).

# CSS 3: Opacity (opacity, rgba):
CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0.

# CSS3 : HSL
The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for:
- *hue*
This is expressed as an angle (between 0 and 360 degrees).
- *saturation*
This is expressed as a percentage.
- *lightness*
This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.


