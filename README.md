# PowerNote 🚀

PowerNote is a modern, all-in-one productivity and learning ecosystem designed to streamline your notes, tasks, and creative ideas. It combines powerful organization tools with AI-driven learning features and a fully customizable interface.

## ✨ Key Features

### 📂 Advanced Organization
- **Smart Folders**: Organize your work with nested folders, custom color-coding, and easy renaming.
- **Drag & Drop**: Seamlessly move files and folders to restructure your workspace.
- **Search**: Global debounced search to find any note, task, or file instantly.

### 📝 Multi-Format Workspace
- **Rich Notes**: Support for Markdown and plain text files with live previews.
- **Interactive Whiteboard**: A vector-based canvas using Konva.js for drawing, text, and embedding images.
- **Media Support**: Upload and preview images and videos directly within your folders.
- **TODO Management**: Task tracking with deadlines, repetition (daily/weekly/monthly), and folder-specific color inheritance.

### 🎓 Learning & AI
- **AI Flashcards**: Automatically generate study cards from your notes using Google Gemini AI.
- **Deck Management**: Group flashcards by folder or global decks, with full management and deletion capabilities.
- **Intelligent Summaries**: Get concise summaries of long notes or documents.

### 🗓️ Dynamic Calendar
- **Task View**: Visualize your deadlines and tasks on a responsive calendar.
- **Day Filtering**: Click on any date to see specific tasks and events for that day.

### 🎨 Total Customization
- **Theme Engine**: Complete control over Accent, Main (Background), and Text colors.
- **Modern UI**: Clean, responsive design with smooth transitions, glassmorphism effects, and intuitive layouts.

### ☁️ Reliability & Sync
- **Offline-First**: Built with Dexie.js (IndexedDB) for fast, reliable local storage.
- **Google Drive Sync**: Securely backup and restore your data using your own Google Drive storage.

## 🛠️ Tech Stack
- **Frontend**: Vanilla JavaScript (ES6+), Modern CSS (Variables, Flexbox, Grid).
- **Database**: [Dexie.js](https://dexie.org/) (IndexedDB wrapper).
- **Canvas**: [Konva.js](https://konvajs.org/) for whiteboard functionality.
- **AI**: [Google Gemini API](https://ai.google.dev/).
- **Icons**: Font Awesome integration.

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/powernote.git
   ```
2. **Open index.html**:
   Since this is a client-side application, you can simply open `index.html` in any modern web browser.
3. **Configure AI (Optional)**:
   - Go to **Settings** in the app.
   - Enter your **Google Gemini API Key** to enable flashcard generation and summaries.
4. **Setup Cloud Backup (Optional)**:
   - In **Settings**, connect your Google account to enable Google Drive sync.

## 🛡️ Privacy
All your data is stored locally in your browser's IndexedDB. No notes or files are sent to any server unless you explicitly enable Google Drive Sync or use the AI features (which send note content to Google's Gemini API).

---
*Built with ❤️ for learners and creators.*
