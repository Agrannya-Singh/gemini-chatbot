

# Gemini Chatbot Clone

A **React-based chatbot clone** using the Google Studio API, featuring a modern UI, persistent conversations, and theme switching. This project demonstrates a modular approach with reusable components and leverages the `lucide-react` icon library.

## Features

- **Chat Interface:** Interactive chat with typing animation and AI responses.
- **Persistent Conversations:** Conversations and settings are saved in `localStorage`.
- **Sidebar:** Switch between conversations, toggle themes, and manage chats.
- **Theme Support:** Light and dark themes with automatic detection.
- **Responsive Design:** Sidebar adapts to screen size.
- **React Lucide Icons:** Clean, scalable icons for UI elements.


## File Structure

| File / Folder | Description |
| :-- | :-- |
| `App.jsx` | Main application logic and state management. |
| `Components/Message.jsx` | Renders individual chat messages. |
| `Components/PromptForm.jsx` | Handles user input and message submission. |
| `Components/Sidebar.jsx` | Sidebar for conversation management and theme toggling. |
| `public/gemini.svg` | Logo displayed on the welcome screen. |
| `.env` | Environment variables (e.g., `VITE_API_URL` for API endpoint). |
| `index.js` / `main.jsx` | Entry point for the React app. |
| `README.md` | Project documentation (this file). |

## Getting Started

### Prerequisites

- Node.js and npm installed
- Google Studio API access
- React project setup


### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/gemini-chatbot-clone.git
cd gemini-chatbot-clone
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory.
    - Add your API endpoint:

```
VITE_API_URL=https://your-google-studio-api-endpoint
```

4. **Start the development server:**

```bash
npm run dev
```


## Usage

- **Send a Message:** Type your prompt and press enter.
- **Switch Conversations:** Use the sidebar to manage chats.
- **Toggle Theme:** Switch between light and dark modes in the sidebar.
- **Responsive UI:** Sidebar auto-collapses on smaller screens.


## Dependencies

- **React** (v18+)
- **lucide-react** (for icons)
- **Google Studio API** (for AI responses)


## Customization

- **Styling:** Modify CSS classes to match your branding.
- **Components:** Extend or replace components in the `Components/` folder.
- **API Integration:** Update the fetch logic in `App.jsx` for different AI backends.


## Credits

- **Made by Agrannya Singh**
- Icons by [lucide-react](https://lucide.dev/)


## License

This project is open-source and available under the MIT License.

