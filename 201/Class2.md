# Class 2 Notes

## Introduction to HTML

1. It’s important to use semantics as doing so gives the content correct meaning and makes the code easy to understand.

2. There are **six** levels of headings. `H1` being the highest and `H6` being the lowest.

3. The `<sup>` element is best used for exponents or ordinal numbers like first or second. While the `<sub>` element is best used for chemical formulas or footnote numbers.

4. If you want to provide the full expansion for an `<abbr>` element, you must use the *title* attribute.

## Learn CSS

1. The most common way to apply CSS to HTML is by using an external stylesheet. The external stylesheet will be a separate file with a `.css` extension that would contain CSS. You can also use an internal stylesheet which resides within an HTML document. For that, all you would have to do is place CSS within a `<style>` element inside the HTML `<head>`. The last option *(and highly advised to not do)* is to do inline styles. You can style a single HTML element by using a `style` attribute.

 Inline Style Example: `<p style="background-color:darkmagenta; color:chartreuse">What is your name?</p>`

2. It’s simply not good practice to use inline styles. It’s more efficient to use an external stylesheet when compared to inline styles, especially if your webpage has more than one page. Also, mixing HTML code with inline styles could make your code hard to read overall.

3. `h2` = Selector

- CSS declarations = `color: black;` and `padding: 5px;`

- Properties = `color:` and `padding:`

## Learn JS

1. What data type is a sequence of text enclosed in single quote marks?: `String`

2. > Addition = `+`

> Strict equality = `===`

> Multiplication = `*`

> Division = `/`

3. Let's say you need to notify a new visitor to your webpage about a specific thing. Well the `alert()` function will make a pop-up box appear in their browser window.

## Making Decisions In Your Code - Conditionals

1. An if statement checks a *condition* and if it evaluates to `true`, then the code block will execute.

2. `else if` = A way to chain extra choices/outcomes to an `if…else` statement.

3. `==` = Equal to

- `!=` = Not equal to

- `>` = Greater than

4. `&&` = AND; chains two or more expressions so that *ALL* of them have to evaluate to true for the whole expression to return true.

- `| |` = OR; chains two or more expressions so *ONE* or *MORE* of them have to individually evaluate to true for the whole expression to return true.
