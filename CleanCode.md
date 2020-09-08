# Chapter 2 Meaningful Names


### Use Intent Revealing Names

Use names that reveal the intent of the function or method
Write code that explains the context and needs no additional knowledge

### Avoid Disinformation

Choose names that describe what is needed to be done
Avoid leaving false clue that obscure the meaning of the code
No inconsistent spelling
No names that vary in small names
e.g. If an item does not contain a list or is not an array then don't name it as such

### Make Meaningful Distinctions

Different names must have different meanings

### Use pronounceable Name

If the name can not be read in a sentence, then dont use it for naming

### Use Searchable Names

Use names that can be searchable across a body of text

### Avoid Encodings

Hard to pronounce,easy to mistype

### Avoid Mental Mapping

Clarity is king;  no one should need to translate your names to anything they know

### Class Names

Must use nouns or noun phrase names. No verbs

### Method Names
Verb or verb phrase names. 
Prefix accessors with get

### Don't Be Cute
Choose clarity over entertainment value

### Pick One Word Per Concept

Stick to one word per abstract per concept
Consitent names for lexicons helps everyone

### Don't Pun
The goal is to make code clear

### Use Solution Domain Names

You can use computer sciency names

### Use Solution Domain Names

Use names drawn from the problem domain

### Add Meaningful Context
Give variables context for readability

### Don't Add Gratuitious Context

# Functions
Functions are the first line of organization in any program.

### Small
The best functions are 2-3, maybe 4 lines long.

### Blocks and Indenting
The blocks within if/while/do while statements should be one line long.

### Do One Thing

A function should only do one thing and do it well.

### One Level Of Abstraction Per Function

Statements within a function must be at the same level of abstraction.

### Reading Code From Top To Bottom: The Stepdown Rule
The code should read like a narrative.

### Descriptive Names
Choose a descriptive name for a small function that does 1 thing
Searching for a good name can lead to well-structured code

### Function Arguments
The ideal number of arguments for a function is 0, then 1, then 2...3 and lastly 4. 
Try as best as you can to avoid having functions that take 3 or more arguments. If you do need to have a function that takes more than 2 arguments, use a data structure such as a hash and pass that hash or other data structure into your function. Testing time increases per function arguments.

### Common Monadic Forms

### Flag Arguments
Try to not pass boolean arguments to a function.

### Verbs And Keywords
Good names describe the intent of functions. 

### Have No Side Effects
Make a function that only does the thing it says it does

### Output Arguments
Have functions change the state of their owning object, avoid if possible, returning an argument in a function

### Command Query Separation
Change or answer, not both

### Prefer Exceptions To Returning Error Codes
Avoid returning exceptions as this violates command query separation.

### Error Handling Is One Thing
Functions that handle errors should only handle errors.

### Don't Repeat Yourself

### How Do You Write Functions Like This?
Code as you usually would, then before you're ready to submit a PR, refactor your functions so that it follows most of the rules listed above
