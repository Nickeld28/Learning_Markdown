## LISTS RULES

### There are two types of lists that Markdown supports:

* Ordered lists (numbered)
* Unordered lists (bulleted)
___

## Ordered lists

To create a numbered list, start a line with a number followed by a dot:

    1. First
    2. Second
    3. Third

#### Example view:

>1. First
>2. Second
>3. Third

Markdown supports lazy numbering. It is important that the list line starts with any number. The first line sets the beginning of the numbering of the entire list:

    55. First - lazy numbering
    1. Second - lazy numbering
    1. Third - lazy numbering

#### Example view:

>55. First - lazy numbering
>1. Second - lazy numbering
>1. Third - lazy numbering

To separate two lists, you can insert a paragraph, a heading or a horizontal ruler between them. \
But for a more convenient separation of lists, you can use a comment, even an empty one:

    1. First list first line
    1. First list second line

    [separator]: # ()

    1. Second list first line
    1. Second list second line

#### Example view:

>1. First list first line
>1. First list second line
>
>[separator]: # ()
>
>1. Second list first line
>1. Second list second line


Inserting empty lines does not separate the lists, but only increases the distance between the lines in the list:

    1. First

    2. Second
    3. Third

#### Example view:

>1. First
>
>2. Second
>3. Third

## Unordered lists

To create unordered lists, use asterisks, pluses, and hyphens as list markers:

    * First list first line
    * First list second line
    - Second list first line
    - Second list second line
    + Third list first line
    + Third list second line

It is important to note that Markdown assigns items to different lists if different markers are used.

#### Example view:

>* First list first line
>* First list second line
>- Second list first line
>- Second list second line
>+ Third list first line
>+ Third list second line


To separate two lists, you can insert a paragraph, a heading, or a horizontal ruler between them. \
But for a more convenient separation of lists, you can use a comment, even an empty one:

    * First list first line
    * First list second line

    [separator]: # ()

    * Second list first line
    * Second list second line


#### Example view:

>* First list first line
>* First list second line
>
>[separator]: # ()
>
>* Second list first line
>* Second list second line

Inserting empty lines does not separate the lists, but only increases the distance between the lines in the list:

    + First

    + Second
    + Third

#### Example view:

>+ First
>
>+ Second
>+ Third

## Nested lists

To create a nested list, you must precede its elements with a tab or four spaces for each subsequent level of nesting. \
A list of one type can be nested within any other:

    1. Ordered list item
        1. Nested ordered list item
            1. Nested ordered list item

    [separator]: # ()

    + Unordered list item
        + Nested unordered list item
            + Nested unordered list item

    [separator]: # ()

    + Unordered list item
        1. Nested ordered list item

    [separator]: # ()

    1. Ordered list item
        + Nested unordered list item

#### Example view:

>1. Ordered list item
>    1. Nested ordered list item
>        1. Nested ordered list item
>
>[separator]: # ()
>
>+ Unordered list item
>    + Nested unordered list item
>        + Nested unordered list item
>
>[separator]: # ()
>
>+ Unordered list item
>    1. Nested ordered list item
>
>[separator]: # ()
>
>1. Ordered list item
>    + Nested unordered list item

## Other elements inside lists

You can add other design elements to list items. For example, paragraphs, blockquotes or code:

    1. First item

        >Blockqoute inside first item

    2. Second item

        Paragraph inside second item

    3. Third item

        ```Example code```

    4. Fouth item

            Example code block

#### Example view:

>1. First item
>
>    >Blockqoute inside first item
>
>2. Second item
>
>    Paragraph inside second item
>
>3. Third item
>
>    ```Example code```
>
>4. Fouth item
>
>        Example code block

### [<<Go back](/Markdown_syntax.md/)
