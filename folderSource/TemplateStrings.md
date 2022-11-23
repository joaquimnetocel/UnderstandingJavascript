# TEMPLATE STRINGS

TEMPLATE STRINGS (OR TEMPLATE LITERALS) PROVIDE AN EASY WAY TO INTERPOLATE VARIABLES AND EXPRESSIONS INTO STRINGS. THE METHOD IS CALLED STRING INTERPOLATION.

TEMPLATE STRINGS ALWAYS USE BACK-TICKS RATHER THAN THE QUOTES TO DEFINE A STRING. USING BACK-TICKS IT IS POSSIBLE TO INTERMOLATE VARIABLES USING `${...}` INSIDE THE STRING. HERE IS A EXAMPLE:

```javascript
const stringColor = "RED";
const numberNumberOfPages = 300;
console.log(`THE BOOK IS ${stringColor} AND HAS ${numberNumberOfPages} PAGES.`);
```

## STRING CONCATENATION WITH `+`

USUALLY, THE PLUS OPERATOR `+` SUMS NUMBERS. BUT, IF THE BINARY `+` IS APPLIED TO STRINGS, IT MERGES (CONCATENATES) THEM:

```javascript
const stringColor = "RED";
const numberNumberOfPages = 300;
console.log("THE BOOK IS " + stringColor + " AND HAS " + numberNumberOfPages + " PAGES.");
```

NOTE THAT IF ANY OF THE OPERANDS IS A STRING, THEN THE OTHER ONE IS CONVERTED TO A STRING TOO.

A BIG DISADVANTAGE OF THIS METHOD, WHEN COMPARED TO THE PREVIOUS METHOD, IS THE NEED TO CONTROL THE BLANK SPACES BETWEEN WORDS.