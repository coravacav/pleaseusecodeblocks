+++
template = "page.html"
+++

# Use Code Blocks for Clarity

In chat rooms and forums, it's crucial to present your code clearly. Instead of just pasting code, use code blocks. This not only maintains the format but also makes it easier for others to understand and help you.

## Why Use Code Blocks?

Code blocks preserve formatting, show your code as-is, and improve readability. They make it easier for others to read and debug your code.

## Creating Code Blocks

**Single-line Code:**

Use backticks (`` ` ``) to create a single-line code block.

For example,
\`println!("i'll be highlighted!")\` turns into a single line of code.

`println!("i'll be highlighted!")`

**Multi-line Code:**

For multiple lines, use three backticks (```). For example:

````
```
line 1 of code
line 2 of code
```
````

This creates a distinct block of code.

You can also add a language identifier to the opening backticks to specify the language. For example: `rust` (shorthands also usually work like `rs` or `tsx`).

**Correct:**

````
Here is my function: ```rust
fn main() {
    println!("Hello, world!");
}
```
````

Here is my function:

```rust
fn main() {
    println!("Hello, world!");
}
```

**Incorrect:**

Here is my function: fn main() {  
 println!("Hello, world!");  
}

Remember, clear questions and well-formatted code increase your chances of getting a helpful response.

For more resources for code-block (and other!) formatting, check out:

-   [GitHub's Guide](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)
-   [Discord's Guide](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-#h_01GY0DAKGXDEHE263BCAYEGFJA)
-   [Slack's Guide](https://slack.com/intl/en-ca/help/articles/204145658-Format-your-messages)
-   [StackOverflow's Guide](https://stackoverflow.com/editing-help#syntax-highlighting)
