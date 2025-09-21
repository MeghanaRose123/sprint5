# WhatsApp Clone - Side by Side

A web-based WhatsApp-like chat interface built with HTML, CSS, and JavaScript. This clone features a chat sidebar, main chat area, and demonstrates simple content moderation with a harassment scoring system.

## Features

- **Modern WhatsApp-style UI**: Responsive and visually similar to the current WhatsApp web interface.
- **Sidebar**: List of chat contacts with avatars, names, statuses, and last message times.
- **Chat Area**: Side-by-side view for Sender and Receiver, showing real-time-like message flow.
- **Harassment Score**: Tracks and displays a cumulative harassment score based on message content.
- **Content Moderation**: Detects and flags harmful language; displays warnings and can block message sending if the score is too high.
- **Moderation Banner**: Notifies users when a message is moderated for harmful content.
- **Profile Switching**: Click sidebar chats to switch between different chat profiles (with separate message histories).
- **Sample Messages**: Demo conversations loaded on first run.
- **Responsive Design**: Works well on desktop and adapts to smaller screens.

## How It Works

- **Sending Messages**: Type and send messages as the sender. The message appears both on the sender and receiver sides.
- **Content Moderation**: The app checks each message for a list of predefined harmful words. If a message is flagged, it's replaced with a moderation note on the receiver's side and a warning banner is displayed.
- **Harassment Score**: Each harmful word increases the cumulative harassment score. Warnings and blocking are triggered at certain thresholds.

## Getting Started

1. **Download or Clone the Repository**
    ```bash
    git clone https://github.com/MeghanaRose123/sprint5.git
    ```

2. **Open the App**
    - Just open `server.html` in your web browser. No build tools or server needed.

## File Structure

- `server.html` — Main application file containing HTML, CSS, and JavaScript.

## Customization

- **Editing Contacts**: Change the `profiles` array in the script section to update sidebar contacts.
- **Moderation Rules**: Edit the `badWords` array to customize which words are flagged.

## Demo

![Screenshot of WhatsApp Clone UI](https://res.cloudinary.com/dlsn7z8dg/image/upload/v1758393836/Screenshot_2025-09-21_001100_mjc8pr.png)

## License

This project is for educational and demonstration purposes only.

## Acknowledgements

- [Font Awesome](https://fontawesome.com/) for icons.
- [RandomUser API](https://randomuser.me/) for avatar images.

---
Made by [MeghanaRose123](https://github.com/MeghanaRose123)
