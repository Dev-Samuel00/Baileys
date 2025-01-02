# Baileys

A WhatsApp Web API client library for Node.js, with a simple and intuitive API.

Features
- Send and receive text, image, video, audio, and document messages
- Support for groups, including creating and managing groups
- Ability to send and receive location messages
- Support for WhatsApp Web API's message acknowledgment and message recall features
- And many more!

Installation
To install Baileys, run the following command:

```
bash
npm install @LordTech-spare/Baileys
```

Example Usage
Here's an example of how to use Baileys to send a text message:

```
const { WAConnection, MessageMedia } = require('@LordTech-spare/Baileys');

const conn = new WAConnection();

conn.on('open', async () => {
    // Send a text message
    await conn.sendMessage('1234567890@c.us', 'Hello, world!');
});

conn.connect();
```

Documentation
For more information on how to use Baileys, please see the (https://github.com/WhiskeySockets/Baileys).

Contributing
Contributions to Baileys are welcome! If you'd like to contribute, please fork this repository and submit a pull request.

License
Baileys is licensed under the ([https://github.com/LordTech-spare/Baileys/blob/master/LICENSE]).

Credits
Baileys was originally created by (https://github.com/WhiskeySockets/Baileys)). This repository is a fork of the original Baileys repository.