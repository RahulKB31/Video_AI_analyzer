# Phidata Video AI Summarizer Agent 🎥🎤🖬

---

## Overview
The **Phidata Video AI Summarizer Agent** is a multimodal AI-powered application that uses advanced language and video processing models to analyze video content and provide insightful responses to user queries. Powered by Gemini 2.0 Flash Exp, the application integrates tools like DuckDuckGo for supplementary research and allows users to upload videos, pose questions, and receive actionable insights.

## Features
- **Video Upload:** Supports video file formats such as MP4, MOV, and AVI for AI-based analysis.
- **AI-Powered Analysis:** Leverages Gemini 2.0 Flash Exp for content and context understanding of videos.
- **Web Research:** Utilizes DuckDuckGo for additional context and supplementary information.
- **Interactive Interface:** Provides a user-friendly Streamlit interface for seamless interaction.
- **Custom Queries:** Users can ask specific questions about the video content, and the AI generates detailed responses.

## Tech Stack
- **Frontend:** Streamlit for user interaction and video playback.
- **AI Models:** Gemini 2.0 Flash Exp.
- **Tools:** DuckDuckGo for additional research.
- **Backend:** Python for logic and API integration.
- **Environment Configuration:** dotenv for managing environment variables.

## Installation
### Prerequisites
1. Python 3.8 or higher installed on your system.
2. `pip` package manager.
3. Google API Key for Gemini 2.0.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate   # For Windows: env\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add your Google API Key:
     ```
     GOOGLE_API_KEY=<your-google-api-key>
     ```

5. Run the application:
   ```bash
   streamlit run app.py
   ```

6. Open the application in your browser at `http://localhost:8501`.

## Usage
1. **Upload a Video:** Click on the file uploader and select a video file (MP4, MOV, or AVI).
2. **Ask a Question:** Use the text area to input your query about the video content.
3. **Analyze Video:** Click the "Analyze Video" button to process the video and get insights.
4. **View Results:** The results are displayed under the "Analysis Result" section.

## Demo Video
[![Watch the Demo Video](C:\Users\Rahul\PycharmProjects\video_summarizer\video_ai.jpg)](https://www.loom.com/share/6ca38f4e78ef4e1db01ea68780ff2704?t=89&sid=c5221bd6-850f-4e9b-b984-70d9c36e47e7)

Click the thumbnail above to watch the demo video on YouTube.

## Project Structure
```plaintext
.
├── app.py                # Main Streamlit application file
├── requirements.txt      # List of dependencies
├── .env                  # Environment variables (not included in repo)
├── README.md             # Project documentation
└── ...                   # Additional files and directories
```

## Requirements
Here’s a list of dependencies required to run the project:
- `streamlit`
- `phi`
- `google-generativeai`
- `dotenv`
- `pathlib`
- `time`
- `tempfile`

Ensure all dependencies are installed by running:
```bash
pip install -r requirements.txt
```

## Limitations
- Requires a valid Google API Key for Gemini 2.0.
- Video analysis may take longer for large files due to processing time.
- Dependent on the availability of external tools like DuckDuckGo for additional context.

## Future Enhancements
- Support for additional video formats.
- Improved response time for large video files.
- Enhanced query capabilities using advanced NLP techniques.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing
Contributions are welcome! If you have ideas or find issues, feel free to submit a pull request or raise an issue.

---