LinkedIn Auto Connector Chrome Extension
Objective
Create a Chrome Extension using the wxt.dev framework and React to automate connection requests on LinkedIn.

Features
Automatically triggers connection requests on the LinkedIn MyNetwork page.

Includes a delay between each request to avoid blocking.

Target URL
The extension is designed to work on the following LinkedIn URL: https://www.linkedin.com/mynetwork/grow/

UI Component
A floating button with the text "Connect with All".

Functionality
When the "Connect with All" button is clicked, the extension will:

Identify all visible Connect buttons on the page.

Trigger a click event for each Connect button.

Include a delay of 1-3 seconds between each connection request.

Installation
Clone this repository.

Open Chrome and go to chrome://extensions/.

Enable "Developer mode" in the top right corner.

Click "Load unpacked" and select the cloned repository folder.

Navigate to the LinkedIn MyNetwork page and use the extension.

Additional Requirements
Ensure code is clean and well-commented.

Handle edge cases, such as no connectable profiles available.
