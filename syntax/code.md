# Code Blocks

Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally.

Here is an example:

```markdown
This is a code block
```

Here is a second example:

```markdown
This is another code block
This time we have two lines of text
```

To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

For example:

```markdown
This is a normal paragraph:

    This is a code block.
```

You can also create code block separated by:

    ```

### Inline code blocks

Inline code blocks can be written using: `

For example:

    This is a `inline code block`

### Syntax highlighting

You can define the language to be used for syntax highlighting by adding the name on the opening tag. Example:

    ```javascript
    var a = {};
    ```

Let's see what some Python code looks like

    ...python
    def display_menu():
        print("Menu:")
        print("1. Which team will win the Super Bowl in 2025?")
        print("2. How will the Jets perform?")
        print("3. Who will win Offensive Rookie of the Year?")
        print("4. Exit")
    ...

