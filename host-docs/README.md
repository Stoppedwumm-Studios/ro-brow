# How to host
## What do I need
- An http or https server
- A brain
- A text editor
- A mouse and a keyboard

## Prepare
Let's start, spin up your server and go into the directory of the files for the site.

To work, the server should be exposed on a port and accessible from the internet

## Create JSON
We do not have an index file right now, so you can choose what name you want for your file

This is our welcome page:

```json
{
  "Header": {
    "Title": "Welcome",
    "UIElements": [
      "UIListLayout"
    ]
  },
  "Body": {
    "Text1": {
      "Type": "TextLabel",
      "BackgroundTransparency": 1,
      "Name": "Text1",
      "Scale": {
        "Y": 0.5,
        "X": 1
      },
      "Text": "Welcome",
      "TextScaled": true,
      "RichText": true
    },
    "Text2": {
      "Type": "TextLabel",
      "BackgroundTransparency": 1,
      "Name": "Text2",
      "Scale": {
        "Y": 0.5,
        "X": 1
      },
      "Text": "To the Roblox Browse Experience",
      "TextScaled": true,
      "RichText": false
    }
  }
}
```
We recommend a unique String Name for every object.

## Explanation
You can see a pattern in the JSON. You define a header, a body and the objects with their properties. This is the structure of HTML, I made it extra like this.

## More things
I will try updating for index files, please prepare for a change
