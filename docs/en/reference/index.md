# Podium reference

TODO: Intro

## Syntax

### General formatting

Basic Markdown formatting is supported, including *italics*, **bold**, ***bold italics***, and ~~strikethrough~~.

### Title slide

### Bullet slides

### Images

### Quotation

### Code

Inline code and code snippets are supported.

Inline code

You can include full code snippets both at the top level and in bullet lists.

To include a snippet at the top level, you could include the following in your `slides.md`:

````markdown
```python
def greeting(arg):
    if arg == 'hello':
        print('Hello World')
    else:
        print(arg)


class Something():
    def __init__(self, *args, **kwargs):
        super().__init__(*args, **kwargs)
```
````

To include a snippet in a bullet list, you could include the following:

````markdown

````

### Footnotes

### Inline content

### Animated transitions

## Keyboard shortcuts

- CMD-Shift-P - Enter presentation mode; or, if in presentation mode, Pause timer
- CMD-P - Open presentation in Print view
- CMD-Q - Quit Podium (exit presentation mode)
- CMD-Tab - Switch displays
- Right/Left arrows - Next/previous slide
- Down/Up arrows - Next/previous slide
- Enter - Next slide
- Home/End - first/last slide
- CMD-A - Switch aspect ratio between 16:9 and 4:3
- CMD-R - Reload slide deck
- CMD-T - Reset timer
