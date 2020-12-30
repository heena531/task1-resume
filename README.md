## Formatting Styles

**Text**

- color: color_name | hexa_code | rgb(0-255, 0-255, 0-255) | rgba(0-255, 0-255, 0-255, 0-1);
- text-align:  left | right | center | justify;
- text-decoration: none | line-through | overline | underline;
- text-transform: none | capitalize | lowercase | uppercase;
- line-height: unit | number;
- text-indent: unit;
- letter-spacing: unit;
- word-spacing: unit;
- text-overflow: clip | ellipsis;

**Font**

- font-size: unit;
- font-family: "Arial", "Times New Roman", "font family 3", "font family 4", [font-category];
- font-style: normal | italic | oblique;
- font-weight: normal | bold | bolder | lighter | number;
- font: font-weight font-size/line-height font-family font-style;

## Backgrounds

- background-color: color_name | hexa_code | rgb(0-255, 0-255, 0-255) | rgba(0-255, 0-255, 0-255, 0-1);
- background-image: url('PATH');
- background-repeat: repeat | no-repeat | repeat-x | repeat-y;
- background-attachment: scroll | fixed;
- background-position: left | center | right | unit || top | center | bottom | unit;
- background-size: auto | contain | cover;

## Box-Model

- margin: unit ||| unit ||| unit ||| unit;
- padding: unit ||| unit ||| unit ||| unit;
- border: style || size || color;
    - style => dashed | dotted | double | solid
    - size => unit
    - color => color_name | hexa_code | rgb(0-255, 0-255, 0-255) | rgba(0-255, 0-255, 0-255, 0-1) | transparent;
- width: unit;
- height: unit;
- min-width: unit;
- max-width: unit;
- min-height: unit;
- max-height: unit;

## Box Shadow & Text Shadow
- box-shadow: [inset] x-axis-distance || y-axis-distance || blur-value || [spread-value] || color;
    - x-axis-distance => unit
    - y-axis-distance => unit
    - blur-value => unit
    - spread-value => unit
    - color => color_name | hexa_code | rgb(0-255, 0-255, 0-255) | rgba(0-255, 0-255, 0-255, 0-1) | transparent;

- text-shadow: [inset] x-axis-distance || y-axis-distance || blur-value || color;
    - x-axis-distance => unit
    - y-axis-distance => unit
    - blur-value => unit
    - color => color_name | hexa_code | rgb(0-255, 0-255, 0-255) | rgba(0-255, 0-255, 0-255, 0-1) | transparent;