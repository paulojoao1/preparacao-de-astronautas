## border ( e outline )

Às bordas da caixa

- value: `<border-style` | `<border-width` | `<border-color>`
    - style: solid | dotted | dashed | double | groove | ridge | inset | outset
    - width: `<length>`
    - color: `<color>`

```css
div {
    /* shorthand */
    border-top: solid 2px; /* top | right | bottom | left */

    /* style */
    border:solid;

    /* width <length> | style */
    border: 2px dotted;

    /* style | color */
    border: outset #f33;

    /* width | style | color */
    border: medium dashed green;
}
```

### E outline?