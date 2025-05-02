# YouTube Transcript API

A simple Flask API that extracts transcripts from YouTube videos using the youtube-transcript-api.

## Features

- Extract transcripts from YouTube videos by providing a YouTube URL or video ID
- Simple REST API with JSON responses
- Health check endpoint

## API Endpoints

- `/transcript?v={video_url_or_id}` - Get the transcript for a YouTube video
- `/` - Health check endpoint

## Technologies Used

- Flask
- youtube-transcript-api
- Render (for deployment)

## Deployment

This application is configured for deployment on Render using the included `render.yaml` file.

## Local Development

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python app.py
   ```

3. Access the API at `http://localhost:5000/transcript?v={video_url_or_id}` 