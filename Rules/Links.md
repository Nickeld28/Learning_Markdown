## LINKS RULES <a id="link-rules"></a>

Markdown supports different types of links depending on how it is classified:

1. **Destination of the Resource**:
   - External links: point to resources outside the current document, website, or project.
   - Internal links: point to resources within the same document, website, or project.

2. **Method of Specifying the Path to the Resource**:
   - [Absolute links](#absolute-links): contain the full URL address of the resource.
   - [Relative links](#relative-links): contain the path to the resource relative to the current location of the document or web page.

3. **Markdown Syntax Style**:
   - [Inline links](#inline-links): created by including the URL address inside square brackets `[]`.
   - [Reference links](#reference-links): created by defining a link with a reference at the bottom of the document and then referencing that footnote in the document text.
   - [Angle brackets links](#angle-brackets-links): created by including the URL or email addresses inside angle brackets `< >`.
   - [Links without brackets](#link-without-brackets): URL addresses displayed as plain text without additional formatting or hyperlink syntax.

4. **Type of Resource**:
   - Links to websites, documents, images, videos, files, etc.

5. **Presence of Attributes or Additional Parameters**:
   - Links with attributes: allow adding additional attributes to the link tag, such as `title`, `target`, `rel`, etc.

6. **Usage of Specific Markdown Features**:
   - [Header links](#header-links): point to a specific header within the same document.
   - [Anchor links](#anchor-links): used for quick navigation to sections or headings within the same document.


Each of these classifications helps to understand different aspects of links and their usage in documents and web pages.

### EXAMPLES:

### Link without brackets <a id="link-without-brackets"></a>

    https://github.com/Nickeld28/Learning_Markdown

#### View:

>https://github.com/Nickeld28/Learning_Markdown

### Angle brackets links <a id="angle-brackets-links"></a>

    <https://github.com/Nickeld28/Learning_Markdown>

#### View:

><https://github.com/Nickeld28/Learning_Markdown>


### Inline links <a id="inline-links"></a>

To link a part of the text, the following syntax is used: `[text](link)`.

    [My Github](https://github.com/Nickeld28)

 #### View:

>[My Github](https://github.com/Nickeld28)

You can make a **tooltip** when you hover over the cursor. To do this, put a space after the link in parentheses and write the tooltip text in quotes:

    [My Github (with tooltip)](https://github.com/Nickeld28 "Nickeld28")

 #### View:

>[My Github (with tooltip)](https://github.com/Nickeld28 "Nickeld28")

### Reference links <a id="reference-links"></a>

Another way to compose a link is creating a link in  reference-style. \
It works like footnotes in books: `[text][footnote name]`. \
With this method of organizing links at the end of the document, you also need to write and compose the footnote itself: `[footnote name]: link`.

    [My Github (with reference)][Nickeld28]

    [Nickeld28]: https://github.com/Nickeld28

 #### View:

>[My Github (with reference)][Nickeld28]
>
>[Nickeld28]: https://github.com/Nickeld28

The same thing, but now using a tooltip:

    [My Github (with reference and tooltip)][Nickeld28 tooltip]

    [Nickeld28 tooltip]: (https://github.com/Nickeld28) "tooltip"

Or you can place a footnote on different lines for convenience if the links are long:

    [My Github (with reference and tooltip)][Nickeld28 tooltip]

    [Nickeld28 tooltip]:
    https://github.com/Nickeld28
    "tooltip"

 #### View:

>[My Github (with reference and tooltip)][Nickeld28 tooltip]
>
>[Nickeld28 tooltip]: https://github.com/Nickeld28 "tooltip"


Sometimes it can be convenient to use footnote text as a title, then you can make it like this:

    [My Github (Footnote text as a title)][]

    [My Github (Footnote text as a title)]:
    https://github.com/Nickeld28 "Footnote text as a title"

 #### View:

>[My Github (Footnote text as a title)][]
>
>[My Github (Footnote text as a title)]:
https://github.com/Nickeld28 "Footnote text as a title"

Reference-style links make the source of your document much more readable.

### Header links

You can create a link as shortcut to any document header. \
Header links are created using the `[Link text](#header-name)` syntax.

    ### Header links

    [Example header link](#header-links)

 #### View:

>[Example header link](#header-links)

### Anchor links <a id="anchor-links"></a>

You can create a link as shortcut not only to the headers, but also to any place in the document using an **anchor link**. \
The necessary place is marked with an anchor using the HTML `<a>` tag with the `id` attribute set to the desired anchor name `<a id="anchor-name"></a>`. \
Anchor links are created using `[Link Text](#anchor-name)` syntax:

    <a id="link-rules"></a>

    [Jump to Link rules](#link-rules)

 #### View:

>[Jump to Link rules](#link-rules)

### Absolute link <a id="absolute-links"></a>

    https://github.com/Nickeld28/Learning_Markdown/blob/main/Markdown_syntax.md

### Relative link <a id="relative-links"></a>

    [<<Go back](/Markdown_syntax.md/)

### [<<Go back](/Markdown_syntax.md/)
