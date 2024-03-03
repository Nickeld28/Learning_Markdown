## RULES FOR ESCAPING CHARACTERS

Some characters in Markdown are service characters and play a special role in creating formatting. If such characters appear in the text, then they need to be escaped for correct display. Otherwise, they may not be displayed, but may also create unnecessary formatting.

### Using Backslash Escapes
To escape a character, use a backslash "\\" in front of it. 

It is not always necessary to do escaping - only in cases where Markdown considers them service.

#### Here is a list of characters that may need escaping:

    \   backslash
    #   hash mark
    +   plus sign
    -   minus sign (hyphen)
    *   asterisk
    _   underscore
    ()  parentheses
    []  square brackets
    {}  curly braces
    !   exclamation mark
    `   backtick
    .   dot

#### Without escaping:

    Files *.jpeg

    Part #3

    . dot

    File__name

    --help

    `A

#### Examples view:

>Files *.jpeg
>
>Part #3
>
>. dot
>
>File__name
>
>--help
>
>`A

#### With escaping:

    \*Title\*

    \# Mark

    1970\. In this year starts the Unix Epoch.

    \_\_main\_\_

    \-\-\-

    \`A\`

#### Examples view:

>\*Title\*
>
>\# Mark
>
>1970\. In this year starts the Unix Epoch.
>
>\_\_main\_\_
>
>\-\-\-
>
>\`A\`

### [<<Go back](/Markdown_syntax.md/)
