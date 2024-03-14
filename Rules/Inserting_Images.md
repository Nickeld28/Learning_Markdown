## INSERTING IMAGES RULES

Inserting an image is similar to adding a link, but there is a difference - you need to put an exclamation mark before the square brackets like `![Image text](link)`.

Adding text is not necessary, it is not even visible. But if the link stops working and the image disappears, then the text is displayed.

### EXAMPLES:

### 1. Image with with a dead link

    ![Image text with a dead link](dead_link)

#### View:

![Image text with a dead link](dead_link)

### 2. Image with an internal (local) link

    ![Markdown logo](/Markdown_logo.png)

#### View:

![Markdown logo](/Markdown_logo.png)

### 3. Image with a clickable link

    [![Image with a clickable link](/Markdown_logo.png)](/Markdown_syntax.md/)

#### View:

[![Image with a clickable link](/Markdown_logo.png)](/Markdown_syntax.md/)

### 4. Image with an external link

     ![Markdown logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/1280px_Markdown_with_White_Background.png/512px-1280px_Markdown_with_White_Background.png)

#### View:

![Markdown logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/1280px_Markdown_with_White_Background.png/512px-1280px_Markdown_with_White_Background.png)


### 5. Image with a tooltip

    ![Image text with broken link](https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png "Markdown logo")

#### View:

![Image text with broken link](https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png "Markdown logo")

### 6. Image with a caption

There is no direct way to caption an image in marldown other than simply writing text below it. But if the Markdown processor you are using works with HTML, you can sign using tags:

    <figure>
       <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png"
             alt="Markdown logo is here" title="Markdown tooltip">
       <figcaption>Markdown logo caption</figcaption>
    </figure>

#### View:

<figure>
   <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png"
         alt="Markdown logo is here" title="Markdown tooltip">
   <figcaption>Markdown logo caption</figcaption>
</figure>


### 7. Resizing an Image

There's no other way to resize an image in Marldown, but if the Markdown processor you're using works with HTML, you can do it using tags:

    <center>
       <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png"
             alt="Markdown logo is here" title="Markdown tooltip" width="300" height="185">
    </center>

#### View:

<center>
   <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png"
         alt="Markdown logo is here" title="Markdown tooltip" width="300" height="185">
</center>

### [<<Go back](/Markdown_syntax.md/)
