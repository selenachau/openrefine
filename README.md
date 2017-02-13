# openrefine
OpenRefine custom transformations

Reverse camelcase: add a space before any 2 character camelcase string
value.replace(/(\p{IsAlphabetic})(?=[A-Z][a-z])/,'$0 ')
