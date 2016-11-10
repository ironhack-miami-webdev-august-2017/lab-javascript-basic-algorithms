![](https://i.imgur.com/1QgrNNw.png)

# Pair Programming | Basic JavaScript Algorithms

Welcome to your first pair-programming exercise in IronHack!

The goal of this exercise is to get you acquainted with the different control structures we have in JavaScript.

Ready?

### Introduction

For this Pair-Programming activity we are going to use Repl.it, a JavaScript [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) that runs in the browser. We can type javascript code in an editor, and then execute it and see the results in the REPL.

Ready to start?

### Environment Setup

- Go to [repl.it](https://repl.it/languages/javascript) and create an account (or login if you have one)
- Open a new repl.it and make sure the language is ==JavaScript==
- Type this in the ==Code Editor== (left panel)

  ```javascript
  console.log("I'm Ready!");
  ```
- Press `run ►`
- If you can see the message on the JavaScript REPL, you're ready!!

  ![](https://i.imgur.com/4TQislb.png)

### Submission

 When you are done and you have checked that everything works fine, go to https://gist.github.com/, create a new [secret gist](https://help.github.com/articles/about-gists/#secret-gists) and send it to your Instructor.
 
 ![](https://i.imgur.com/ux5em6j.png)

:::info
**Remember:** Remember to add the extension of the file `fileName`**.js** in the *"Filename including extension"* input box so you can enjoy [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) in your gist
:::
 
### Exercise

#### Names and Input

1. Create a variable `hacker1` with the driver's name

2. Print `"The driver's name is XXXX"` 

3. Create a variable `hacker2` and [ask the user](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) for the navigator's name

4. Print `"The navigator's name is YYYY"`

#### Conditionals

5. Depending on which name [is longer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length), print:
	- `The Driver has the longest name, it has XX characters` or 
	- `Yo, navigator got the longest name, it has XX characters` or
	- `wow, you both got equally long names, XX characters!!`

#### Loops

6. Print all the characters of the driver's name, separated by a space and [in capitals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase)
  ie. `"J O H N"`
  
7. Print all the characters of the navigator's name, in reverse order. 
  ie. `"nhoJ"`
  
8. Depending on the [lexicographic order](https://en.wikipedia.org/wiki/Lexicographical_order) of the strings, print:
  - `The driver's name goes first`
  - `Yo, the navigator goes first definitely`
  - `What?! You both got the same name?`

#### Bonus Time!

9. Ask the user for a new string and check if it's a [Palindrome](https://en.wikipedia.org/wiki/Palindrome). Examples of palindromes:
	- "A man, a plan, a canal, Panama!"
	- "Amor, Roma"
	- "race car"
	- "stack cats"
	- "step on no pets"
	- "taco cat"
	- "put it up"
	- "Was it a car or a cat I saw?" and "No 'x' in Nixon".

10. Go to [lorem ipsum generator](http://www.lipsum.com/) and:
  - Generate 3 parragraphs. Store the text in a String
  - Make your program count the number of words in the string
  - Make your program count the number of times the latin word [`et`](https://en.wiktionary.org/wiki/et#Latin)appears

## Useful Resources

- [prompt() - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) | Ask user for input
- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
