# Gemini AI Chatbot

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E77F0?style=for-the-badge&logo=google-gemini&logoColor=white)

A full-stack AI chatbot application built with Spring Boot and React that connects to the Google Gemini API. This project features a real-time, streaming response interface for a natural and interactive user experience.


---

### ✨ Features

* **Real-Time Streaming:** Responses from the AI are streamed word-by-word for a dynamic, conversational feel.
* **Reactive Backend:** Built with Spring WebFlux to handle asynchronous API calls efficiently without blocking threads.
* **Modern Frontend:** A clean, responsive single-page application (SPA) built with React and styled with Bootstrap.
* **Secure API Integration:** Securely communicates with the Google Gemini API with API keys managed on the backend.

---

### 🛠️ Tech Stack

| Category      | Technology                               |
| ------------- | ---------------------------------------- |
| **Frontend** | React.js, Vite, Bootstrap, Axios         |
| **Backend** | Spring Boot, Java, Spring WebFlux, Maven |
| **AI Service**| Google Gemini API                        |
| **Tools** | VS Code, IntelliJ IDEA, Git              |

---

### 🚀 Getting Started

Follow these instructions to get a local copy of the project up and running for development and testing purposes.

#### Prerequisites

* Node.js & npm (v18 or later)
* Java JDK (v17 or later)
* Maven
* A Google Gemini API Key. You can get one from [Google AI Studio](https://aistudio.google.com/app/apikey).

#### ⚙️ Backend Setup (IntelliJ IDEA)

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/VairagPatel/gemini-chatbot.git](https://github.com/VairagPatel/gemini-chatbot.git)
    cd gemini-chatbot
    ```

2.  **Navigate to the backend directory:**
    ```sh
    cd API 
    ```

3.  **Set up your API Key:**
    * Go to the `src/main/resources` folder.
    * Open the `application.properties` file.
    * Add your Google Gemini API key:
        ```properties
        gemini.api.key=YourSecretGeminiApiKeyGoesHere
        ```

4.  **Run the backend server:**
    ```sh
    ./mvnw spring-boot:run
    ```
    The backend will start on `http://localhost:8080`.

#### 🎨 Frontend Setup (VS Code)

1.  **Navigate to the frontend directory** (from the root folder):
    ```sh
    cd frontend 
    ```
    *(Note: The video may show the frontend in the root; adjust the `cd` command if needed.)*

2.  **Install NPM packages:**
    ```sh
    npm install
    ```

3.  **Run the frontend development server:**
    ```sh
    npm run dev
    ```
    Open [http://localhost:5173](http://localhost:5173) in your browser to see and interact with the application.
