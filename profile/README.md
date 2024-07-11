# SiteProof 
###### AI Web Analyzing Tool 

> Team Members: Ariel Andres Lopez Correa | Gerardo Diaz Lopez | Jose Avir Gariel Guerrero | Jose Pablo Naime Garcia | Maria Carelia Ibarra Vasquez | Maximiliano Villegas Garcia

## Project Description

SiteProof is an AI-powered tool designed to generate use cases for websites, aiding developers and testers in their work. This project consists of two main components: a Chrome extension and a server. The Chrome extension allows users to run SiteProof on any website, provide context, and generate use cases. The image of the website is sent to a local server, which processes the data using a machine learning model and returns a response displayed within the Chrome extension.

## Table of Contents

- [Installation](#installation)
  - [Chrome Extension](#chrome-extension)
  - [Server](#server)
- [Usage](#usage)
  - [Running the Chrome Extension](#running-the-chrome-extension)
  - [Providing Context](#providing-context)
- [License](#license)

## Installation

### Chrome Extension

1. Clone the Chrome extension repository:
   ```bash
   git clone [https://github.com/yourusername/siteproof-extension.git](https://github.com/TC3002B-31/ChromeExtension)
   ```

2. Open Chrome and navigate to `chrome://extensions/`.

3. Enable "Developer mode" using the toggle switch in the top right corner.

4. Click "Load unpacked" and select the \`siteproof-extension\` directory.

### Server

1. Clone the server repository:
   ```bash
   git clone [https://github.com/yourusername/siteproof-server.git](https://github.com/TC3002B-31/Server)
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the server:
   ```bash
   python app.py
   ```

4. A GUI will pop up, add your OpenAI API and your preferred port **Make sure that the chrome extension is pointing to the same port**

## Usage

### Running the Chrome Extension

1. Open the Chrome extension on any website you want to analyze.

2. Click on the SiteProof icon in the Chrome toolbar to open the extension interface.

### Providing Context

1. In the extension interface, provide the necessary context about the website.

2. Click the Submit button and wait for a response.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
