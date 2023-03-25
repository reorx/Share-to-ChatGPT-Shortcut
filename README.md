# Share to ChatGPT Shortcut

The Share to ChatGPT feature is an Apple Shortcut that allows users to share highlighted text to ChatGPT while also including personalized prompts. Additionally, the response message will automatically be copied to the user's clipboard.

## Installation

- 2023-03-25: https://www.icloud.com/shortcuts/9cd41f860ef2473aa9d69931b1cb0e19

## Setup and Usage

After installation, the shortcut will be available in the Shortcuts app. Follow the steps below to set up the shortcut:

1. Open the shortcut
2. After clicking "Done," enter your OpenAI API key in the dialog box. You will then receive a notification that confirms the configuration path.
3. Type something like "hello" for testing purpose, and choose a builtin prompt like "chat".
4. Click "Allow" for every confirmation dialog. Note that you'll see a confirmation for allowing to send "1 dictionary" to "api.openai.com" the next time you run the shortcut, which looks kinda weird but is just a side-effect of storing the API key in a file, you should click "Always Allow" to make the shortcut work properly.

| Step 1 | Step 2 | Step 3 | Step 4 |
| :----: |:------:|:------:|:------:|
| <img width="200" src="images/setup/step-1.PNG" /> | <img width="200" src="images/setup/step-2.PNG" /><img width="200" src="images/setup/step-2-notification.jpg" /> | <img width="200" src="images/setup/step-3.PNG" /> | <img width="200" src="images/setup/step-4.JPEG" /> <img width="200" src="images/setup/step-4-extra.PNG" />|

To create an easily accessible shortcut for daily use, follow these steps:

1. Open the share sheet by highlighting some text and tapping the share button.
2. Scroll to the bottom and select "Edit Actions".
3. Scroll to the bottom again and choose "Share to ChatGPT".
4. This will place the shortcut at the top of the share sheet for easy access.

| Step 1 | Step 2 | Step 3 | Step 4 |
| :----: |:------:|:------:|:------:|
| <img width="200" src="images/share-sheet/step-1.jpg" /> | <img width="200" src="images/share-sheet/step-2.jpg" /> | <img width="200" src="images/share-sheet/step-3.jpg" /> | <img width="200" src="images/share-sheet/step-4.jpg" /> |

Finally, let's see how to use the shortcut in action. Here's an example to use the shortcut to revise a sentence:

1. Highlight the text and click "Share" in the tooltip
2. Click "Share to ChatGPT" in the share sheet
3. Choose "revise" in the dialog
4. Preview the result, which has already been copied to the clipboard

| Step 1 | Step 2 | Step 3 | Step 4 |
| :----: |:------:|:------:|:------:|
| <img width="200" src="images/revise/step-1.jpg" /> | <img width="200" src="images/revise/step-2.jpg" /> | <img width="200" src="images/revise/step-3.jpg" /> | <img width="200" src="images/revise/step-4.PNG" /> |


## Prompts

The shortcut has the following built-in prompts.

You can also add your own prompts by editing the shortcut.
