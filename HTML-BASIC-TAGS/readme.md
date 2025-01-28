# HTML Basic Tags Demonstration

This HTML file demonstrates various fundamental HTML tags used in web development.

## Tags Used

### 1. **Heading Tags**
   - Used to define headings in a hierarchical order:
     ```html
     <h1>Heading 1</h1> <!-- Largest heading -->
     <h2>Heading 2</h2>
     <h3>Heading 3</h3>
     <h4>Heading 4</h4>
     <h5>Heading 5</h5>
     <h6>Heading 6</h6> <!-- Smallest heading -->
     ```

### 2. **Paragraph Tag**
   - Used to create text blocks:
     ```html
     <p>This is a simple paragraph.</p>
     ```

### 3. **Line Break Tag**
   - Used to break content to a new line:
     ```html
     <p>My name is Rohit Shewale <br/> I'm a front-end developer</p>
     ```
   - Note: `<br>` is a void tag (no closing tag).

### 4. **Center Tag**
   - Centers content horizontally:
     ```html
     <center>
         <p>This is centered content.</p>
     </center>
     ```

### 5. **Preformatted Text Tag**
   - Retains the original formatting of text:
     ```html
     <pre>
         function testFunction(){
             return alert("This is a preformatted text example.");
         }
     </pre>
     ```

### 6. **Non-Breaking Space**
   - Prevents content from splitting into a new line:
     ```html
     <p>I'm post graduated &nbsp; I'm currently working in Infosys</p>
     ```

### 7. **Meta Tags**
   - Provide metadata about the document:
     ```html
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     ```

## How to Use
1. Save the provided HTML code in a `.html` file (e.g., `index.html`).
2. Open the file in a browser to see the output.

## Sample Code
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Basic Tags</title>
</head>
<body>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

    <p>This is a simple paragraph.</p>
    <p>My name is Rohit Shewale <br/> I'm a front-end developer</p>

    <center>
        <p>This is centered content.</p>
    </center>

    <pre>
        function testFunction(){
            return alert("This is a preformatted text example.");
        }
    </pre>

    <p>I'm post graduated &nbsp; I'm currently working in Infosys</p>
</body>
</html>
