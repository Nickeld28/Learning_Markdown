## CODE RULES

### Markdown has several ways to highlight source code:

* Highlighting a code fragment in the text using backticks
* Highlighting multiple lines of code using backticks on both sides
* Creating а block code using tab or four spaces at the beginning of a line
___

## Code fragment

    Here is text with a `code fragment` in this paragraph.

#### Example view:

>Here is text with a `code fragment` in this paragraph.

## Escaping backticks

If there is a "`" character inside the code, then to save it you need to wrap the code fragment in double backticks:

    ``Expample of code with `foo` function``

#### Example view:

``Expample of code with `foo` function``

## Multiple lines of code

It is often necessary to highlight several lines of code at once:

    ```
    # First line of code
    # Second line of code
    # Third line of code
    ```

#### Example view:

>```
># First line of code
># Second line of code
># Third line of code
>```

## Highlighting the language syntax

If you wrap the code with three backticks, then after the first three you can specify the programming language - then Markdown will correctly highlight the code elements:

    ```python
    def foo(x: int) -> float:
        for i in range(3):
            x *= 0.5
        return x
    ```

#### Example view:

```python
def foo(x: int) -> float:
    for i in range(3):
        x *= 0.5
    return x
```

## Block of code

There is another way to highlight code - use a code block.

#### Example view:

    def foo(x: int) -> float:
        for i in range(3):
            x *= 0.5
        return x

### [<<Go back](/Markdown_syntax.md/)
