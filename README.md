# Modal Display Calculator element

Built on the Polymer Seed, for reusability, this element presents a modal calculator display. As simple to include in your project as any other polymer element. Capabable of: addition, subtraction, multiplication and division. Returns a value to the parent, accesible through the 'final-value' property.

Example:
```html
<fbv-calculator-modal final-value="{{value}}">
    // An insertion point is created, which responds to tap/click, where you can place a button,
    // word, icon, ... in order to open the calculator dialog
    // eg. button
    <paper-icon-button icon="remove"></paper-icon-button>
</fbv-calculator-modal>
```

## Demo Page

Visit http://nickBor.github.io/fbv-calculator-modal to demo the element.

You will find all the documentation provided for the element and a working demo of the element.

## Install with Bower

Run:

`bower install nickBor/fbv-calculator-modal`

to download the element into your bower dependencies folder. Then import `fbv-calculator-modal.html` into your project, elements folder or custom element, as you would with any other polymer element.

To save the dependency to the bower.json file, run:

`bower install --save nickBor/fbv-calculator-modal`


## Coming up

Currently under development. Next changes on the list:

- Complete testing of functionalities and posible uses/missuses
- Wire up styles for user custom stylings to be available
- Responsive behaviour. Ideas still flowing here.
