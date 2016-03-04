# phone-formatter
Polymer element used to add formatting to 10-digit phone numbers.


Example:
```html

    <phone-formatter number-input="0123456789" format="parentheses"></phone-formatter>
```

Options: 
The following format options are supported:
- default (no user input given for 'format') - results in a number formatted with dashes: 012-345-6789
- "parentheses" - results in (012) 345-6789
- "spaces" - results in 012 345 6789
- "periods" - results in 012.345.6789

## Install

* bower install --save DigElements/phone-formatter
* add a line to import the html file like this:

`<link rel="import" href="../bower_components/phone-formatter/phone-formatter.html">`

## Testing

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).
