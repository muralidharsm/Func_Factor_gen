# Fun Fact Generator Web App

This is a simple Python-based web application that fetches random facts from the `uselessfacts.jsph.pl` API and displays them on a web interface. The app uses `PyWebIO` for creating an interactive browser-based GUI and `requests` to retrieve the data.

## Features
- Fetches random facts using the `GET` method from the [uselessfacts API](https://uselessfacts.jsph.pl/).
- Displays facts dynamically on a web interface built with `PyWebIO`.
- Lightweight and easy-to-implement Python script that requires no prior knowledge of HTML or JavaScript.

## Prerequisites
Before running the app, ensure you have the following Python modules installed:

1. **requests** - for making API requests.
2. **PyWebIO** - for creating the web interface.
3. **json** - for handling the API response.

You can install the required packages using `pip`:

```bash
pip install pywebio requests
