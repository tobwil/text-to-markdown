# text-to-markdown
![image](https://github.com/tobwil/text-to-markdown/assets/72387477/3b66ef0c-3838-4334-926b-827c18db4495)
## 📄 TRY IT OUT ➡️ https://tobwil.github.io/text-to-markdown/converter.html

#### Introduction

The given code is a simple HTML text editor that allows users to format text and convert it to Markdown. It provides a toolbar with various formatting options such as bold, italic, underline, header styles, font size, bullet points, and numbering.

#### Implementation

The text editor is implemented using the `contenteditable` attribute, which makes the `div` element editable. Users can type and format text directly in the editor. The toolbar buttons execute the corresponding `document.execCommand()` function to apply the formatting to the selected text.

#### Additional Functionality

There are two additional buttons at the bottom of the editor.

1.  The "Convert to Markdown" button uses the Turndown library to convert the formatted text in the editor to Markdown format. The converted Markdown is displayed in a separate `div` with the id "markdownOutput".
2.  The "Copy to Clipboard" button copies the Markdown output to the clipboard.

#### Styling

The code also includes some basic styling using the Tailwind CSS framework to make the editor and toolbar visually appealing.

#### Usage

Overall, this HTML text editor provides a simple and user-friendly interface for formatting text and converting it to Markdown. It can be used in various web applications or content management systems where users need to write and format text.
