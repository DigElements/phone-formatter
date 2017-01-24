# phone-formatter

A Polymer Element used to add formatting to telephone numbers.

### Example
```html
<phone-formatter input="0123456789" format="parentheses"></phone-formatter>
```

### Options

The format property supports the following options:

| Option | Examples |
|--------|----------|
| "dashes" | 012-345-6789, 111-222-333-4444 |
| "parentheses" | (012) 345-6789, +111 (222) 333-4444 |
| "periods" | 012.345.6789, 111.222.333.4444 |
| "spaces" | 012 345 6789, 111 222 333 4444 |
| an empty or unsupported option | 0123456789, +1112223334444 |

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

