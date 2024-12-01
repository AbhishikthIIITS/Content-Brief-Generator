# Content Brief Generator

The **Content Brief Generator** is a web application designed to help users create detailed, SEO-optimized content briefs for any topic using generative AI.

## Setup and Usage

### Prerequisites

Ensure you have the following installed:
- **Node.js** (v14 or later)
- **npm** or **yarn**
- **Google Generative AI API Key**

### Backend Setup

1. Navigate to the `backend` folder:
    ```bash
    cd backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file and add your Google API key:
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

4. Start the backend server:
    ```bash
    node index.js
    ```
    The backend will run on `http://localhost:5000`.

### Frontend Setup

1. Navigate to the `frontend` folder:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the React application:
    ```bash
    npm start
    ```
    The frontend will run on `http://localhost:3000`.

### How to Use

1. Open the application in your browser at `http://localhost:3000`.
2. Enter a topic in the input field (e.g., "The Future of Remote Work").
3. Click the **Generate** button to create a content brief.
4. View the generated brief displayed dynamically on the screen.

### Deployment

- **Frontend**: [https://content-brief-generator-frontend.vercel.app/](https://content-brief-generator-frontend.vercel.app/)
- **Backend**: [https://content-brief-generator-backend-1.onrender.com/](https://content-brief-generator-backend-1.onrender.com/)
