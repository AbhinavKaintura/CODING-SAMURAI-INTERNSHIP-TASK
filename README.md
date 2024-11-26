
# TaskHive 📝

TaskHive is a simple and intuitive React-based note-taking web application that allows users to create, manage, and delete notes effortlessly.

## 🌟 Features

- **Dynamic Note Creation**: Expandable input area with smooth UI transitions
- **Easy Note Management**: 
  - Add notes with titles and content
  - Delete individual notes with a single click
- **Responsive Design**: Clean, minimalist interface
- **State Management**: Utilizes React's useState for efficient state handling

## 🚀 Technologies Used

- **Frontend**: React.js
- **UI Components**: Material-UI (MUI)
  - `@mui/material` for components like Fab and Zoom
  - `@mui/icons-material` for icons
- **State Management**: React Hooks (useState)

## 🔧 Key Components

1. **CreateArea.jsx**: 
   - Handles note creation
   - Provides an expandable textarea
   - Manages note input state

2. **Note.jsx**: 
   - Renders individual notes
   - Provides delete functionality
   - Displays note title and content

3. **App.jsx**: 
   - Central state management
   - Handles adding and deleting notes
   - Renders all notes and core app structure

## 📦 Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run the application: `npm run dev`

## 🌈 Future Improvements

- Add note editing functionality
- Implement local storage
- Add note categorization
- Create search/filter capabilities
