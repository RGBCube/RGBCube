Here is the stuff that I eventually want to do.

### HTML Preprocessor
```kt
html(lang = "en") {
    head {
        title("Foo Bar")
    }
    body {
        p {"My Paragraph"}
    }
}
```
Makes:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Foo Bar</title>
    </head>
    <body>
        <p>My Paragraph</p>
    </body>
</html>
```
Or something, but with removed bloat, idk.
