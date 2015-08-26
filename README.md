# fbv-calculator-modal

Built on the Polymer Seed, for reusability, this element presents a modal calculator display. As simple to include in your project as any other polymer element. Capabable of: addition, subtraction, multiplication and division. Returns a value to the parent, accesible through the 'value' property.

Example:
```html
<fbv-calculator-modal value="{{value}}"></fbv-calculator-modal>
```

## Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--paper-card-header-color` | The color of the header text | `#000`
`--paper-card-header` | Mixin applied to the card header section | `{}`
`--paper-card-content` | Mixin applied to the card content section| `{}`
`--paper-card-actions` | Mixin applied to the card action section | `{}`
`--paper-card` | Mixin applied to the card | `{}`