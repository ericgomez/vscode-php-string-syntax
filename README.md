# PHP String Syntax

**PHP String Syntax** is a Visual Studio Code extension that highlights SQL, HTML, and JavaScript embedded in PHP strings. It uses the `/*sql*/`, `/*html*/`, and `/*js*/` markers to identify and apply syntax highlighting to SQL queries, HTML content, and JavaScript code, ensuring compatibility with other editors by not altering the internal text content.

## Features

- **SQL, HTML, and JavaScript Syntax Highlighting**: Automatically detects SQL queries preceded by `/*sql*/`, HTML content preceded by `/*html*/`, and JavaScript code preceded by `/*js*/`, applying the appropriate syntax highlighting.
- **Compatibility with Other Editors**: The use of `/*sql*/`, `/*html*/`, and `/*js*/` comments does not interfere with syntax in other editors or IDEs.
- **Multiline String Support**: Works seamlessly with queries, HTML content, and JavaScript code spread across multiple lines.

### Current Support

- **HTML**
- **SQL**
- **JavaScript**

### Example

#### HTML Example
![html](./images/html_example.png)

#### SQL Example
![sql](./images/sql_example.png)

#### JavaScript Example
```php
$jsCode = /*js*/ "console.log('Hello, World!');";
```

Visual Studio Code will apply SQL, HTML, and JavaScript syntax highlighting to the content of the strings, improving readability and streamlining development.

### Installation

1. Open Visual Studio Code.
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on Mac).
3. Search for **PHP String Syntax**.
4. Click "Install."

### Feedback

Your feedback is invaluable! If you encounter any issues or have suggestions for improvements, please [report them](https://github.com/ericgomez/vscode-php-string-syntax/issues) here.

### License

This extension is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

Enjoy coding with **PHP String Syntax**! 🚀
