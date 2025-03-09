# YouTube Video Transcript Feedback System

This project implements a **YouTube Video Transcript Feedback System** using **LangChain**, **LangGraph**, and **Groq's LLM**. It automates the process of extracting a transcript from a YouTube video and generating structured feedback based on the content.

## Features

- **Transcript Extraction**: Automatically extract the transcript from a YouTube video.
- **Content Analysis**: Analyze the transcript to understand the content.
- **Feedback Generation**: Generate detailed and structured feedback based on the transcript content.
- **State Management**: Use LangGraph to manage the flow from extraction to feedback generation.
- **LLM Integration**: Leverage Groq's LLM to generate human-like feedback.

## Tech Stack

- **Python**
- **LangChain**
- **LangGraph**
- **Groq LLM**
- **YouTube Transcript API**
- **Dotenv** for managing environment variables

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables by creating a `.env` file in the root directory:

   ```plaintext
   GROQ_API_KEY=<your-groq-api-key>
   ```

## Usage

1. Run the Jupyter Notebook to initiate the transcript feedback generation process.

2. The notebook follows a multi-step process:

   - **Input Video URL**: Provide the YouTube video URL.
   - **Extract Transcript**: Automatically extract the transcript from the video.
   - **Generate Feedback**: Use LLM to generate structured feedback.
   - **Display Feedback**: The feedback is displayed in the notebook output.

3. The output will include:

   - **Video URL**
   - **Extracted Transcript**
   - **Generated Feedback**

## Example Workflow

1. **Input URL**: Provide a YouTube video link like `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
2. **Extract Transcript**: The API extracts the full transcript of the video.
3. **Generate Feedback**: LLM generates structured feedback based on the transcript.
4. **Display Feedback**: The feedback is displayed for review.

## Environment Variables

Ensure you set the following environment variable in your `.env` file:

```plaintext
GROQ_API_KEY=<your-groq-api-key>
```

