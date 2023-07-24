# OOP Modal README

## Description

This code implements a simple Object-Oriented Programming (OOP) approach to create a modal (popup) window in a web page. The modal provides a way to display additional content on top of the main page content without navigating away. It contains a title, some text, and a button to close the modal.

## Features

- **Modal Display**: A modal can be displayed by clicking the "OPEN MODAL" button.
- **Modal Close**: The modal can be closed by clicking the "Close Modal" button within the modal window.
- **Dynamic Content**: The modal content (title and text) can be dynamically changed through a method provided by the Modal class.

## How to Use

1. Clone or download the HTML file containing the code to your local machine.
2. Open the HTML file in a web browser. You can simply double-click the file to open it in the default browser.
3. The web page will display a heading, a list of instructions, and a button labeled "OPEN MODAL."
4. Click the "OPEN MODAL" button to reveal the modal window with the default title and text.
5. To close the modal, click the "Close Modal" button inside the modal window.

## Modifying Modal Content

If you want to modify the default content displayed in the modal, you can do so through the provided `Modal` class methods:

1. `changeContent(title, text)`: Use this method to change the title and text displayed in the modal. Pass the new `title` and `text` as arguments. If you only want to change the title or text, you can pass `undefined` for the parameter you want to keep unchanged.

## Code Structure

The code consists of an HTML document containing the modal structure and basic styling, along with an embedded JavaScript code that defines the `Modal` class and handles the modal functionality.

- **HTML**: The HTML part defines the modal structure, including the modal container, title, text, and close button. It also contains an open button to trigger the modal.
- **CSS**: Some basic CSS is included to style the modal, making it appear as a centered, fixed-positioned popup with a shadow effect.
- **JavaScript**: The JavaScript code defines the `Modal` class, which encapsulates the modal's behavior. It provides methods to open, close, and change the modal content. The script also handles the event listeners for the "OPEN MODAL" and "Close Modal" buttons, interacting with the `Modal` instance.
