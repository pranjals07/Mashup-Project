# Mashup Project

This project is a **Streamlit app** that provides an interactive interface for creating custom audio mashups using audio from YouTube videos. Users can download, trim, and merge audio clips seamlessly to create unique mashups.

---

## Features

1. **Download YouTube Audio**
   - Fetch audio tracks from YouTube videos by providing a video URL.

2. **Trim Audio**
   - Select specific time ranges to trim the audio according to your needs.

3. **Merge Audio Clips**
   - Combine multiple audio clips into a single audio file to create your mashup.

4. **Export and Share**
   - Save the final mashup as an audio file and share it easily.

---

## Installation

Follow these steps to set up and run the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/mashup-project.git
   cd mashup-project
   ```

2. **Install Dependencies**
   Ensure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```

4. **Access the App**
   Open the provided local URL (e.g., `http://localhost:8501`) in your browser to use the app.

---

## Usage

1. **Provide a YouTube URL**
   - Input the URL of the YouTube video from which you want to extract audio.

2. **Trim the Audio**
   - Use the interactive sliders to select the start and end times for trimming the audio clip.

3. **Merge Audio Clips**
   - Upload or select multiple trimmed audio clips to combine them into a single file.

4. **Export the Mashup**
   - Save the final mashup as an audio file and download it to your device.

---

## File Structure

- **app.py**: Main Streamlit application script.
- **requirements.txt**: List of Python dependencies.
- **README.md**: This file.
- **assets/**: Directory for any additional resources or static files.

---

## Dependencies

This project uses the following Python libraries:
- **Streamlit**: For creating the interactive web application.
- **pytube**: For downloading audio from YouTube videos.
- **pydub**: For trimming and merging audio clips.
- **ffmpeg**: Required for audio processing by `pydub`.

Make sure `ffmpeg` is installed on your system. For installation instructions, visit the [FFmpeg website](https://ffmpeg.org/).

---

## Contributions

Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and submit a pull request.

---



