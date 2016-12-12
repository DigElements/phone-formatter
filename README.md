# phone-formatter

A Polymer Element used to add formatting to 10-digit phone numbers.

### Example
```html
<phone-formatter input="0123456789" format="parentheses"></phone-formatter>
```

### Options

The following format options are supported:
- default (no user input given for 'format') - results in a number formatted with dashes: 012-345-6789
- "parentheses" - results in (012) 345-6789
- "spaces" - results in 012 345 6789
- "periods" - results in 012.345.6789

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

