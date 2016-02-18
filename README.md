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
