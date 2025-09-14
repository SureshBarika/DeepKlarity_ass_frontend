
## DeepSeek Resume Analyzer Frontend

This is the frontend for the DeepSeek Resume Analyzer application, built with React and Vite.

### File Structure

- `public/` - Static assets
- `src/` - Source code
  - `api.js` - Handles API requests to the backend
  - `App.jsx` - Main application component
  - `main.jsx` - Entry point
  - `index.css`, `styles.css` - Global styles
  - `assets/` - Images and icons
  - `components/` - UI components:
	 - `UploadTab.jsx` - Resume upload interface
	 - `HistoryTab.jsx` - Displays upload history
	 - `ResumeDetailsModal.jsx` - Shows parsed resume details
- `package.json` - Project dependencies and scripts
- `vite.config.js` - Vite configuration

### Local Setup Instructions

1. **Navigate to the frontend folder:**
	```powershell
	cd frontend
	```

2. **Install dependencies:**
	```powershell
	npm install
	```

3. **Start the development server:**
	```powershell
	npm run dev
	```

4. **Access the app:**
	Open your browser and go to `http://localhost:5173` (default Vite port).

### Main Functionalities

- **Resume Upload:** Upload PDF resumes to the backend for analysis.
- **History Tab:** View previously uploaded resumes and their analysis results.
- **Resume Details Modal:** Display extracted information (skills, experience, education) from resumes.
- **API Integration:** Communicates with the backend for resume parsing and data retrieval.

---
For backend setup, see the backend folder's README.
