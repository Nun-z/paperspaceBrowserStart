# paperspaceBrowserAccess

Start, shutdown, or restart a [Paperspace](http://www.paperspace.com/) cloud computer using a regular web browser by accessing a simple website, without entering your credentials.

Anyone who isn't a complete idiot can see your API key and machine hostname if you use this, so I wouldn't recommend using this in its current state.

You can obfuscate the HTML here: https://www.wmtips.com/tools/html-obfuscator/

## Reason
You can use this to quickly send commands to your Paperspace VM, or you can give it to a client so that they will be able to access their VM without knowing your credentials.

## Instructions
1. Get an API key in the Paperspace console.
2. Add the machine id and the api-key to the source code of the file.
3. Upload `index.html` to your server or webspace.
