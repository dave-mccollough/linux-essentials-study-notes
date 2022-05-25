# Quoting

Preserve the input that contains special characters or spaces
Quoting is used to disable special treatment of certain characters and words, as well as to prevent parameter expansion and preserve what is quoted.

## Methods
**Escape Character**  
A non-quoted backslash `\` is the bash escape character and preserves the literal value of the next following character, with the single exception of a new line `\n`.
- `var1 = Some\ Value`
- `echo $var1`
- Returns:  `Some Value`

**Single Quotes**
Single quotes `'` preserve the literal value of every character contained within the quotes, including the escape character.
- `echo 'this\ is $var1'`
- Returns:  `this\ is $var1`


**Double Quotes**
Double quotes `"` perserver the literal value of most characters contained within the quotes, exceptions include 
`$`(for variables)
`'`(for single quoting)
`\`(For escaping a character)

- `echo "this\ is $var1"`
- Returns:  `this\ is Some Value`

- `echo "this is a "quote"`
- Returns:  `this is a quote`

- `echo "this is a \"quote"\"`
- Returns:  `this is a "quote"`
- Adding the backslash (`\`) preserves the quotes.