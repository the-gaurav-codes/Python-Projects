# 📖 PDF to Audio Book using Python

This is a Python project that converts the text from a PDF file into an audiobook.  
You can choose to either **listen live** to the content or **save it as an `.mp3`** file.

## 🔧 Features

- 📂 Select any PDF file using a file dialog
- 🗣️ Read the text aloud using a text-to-speech engine
- 💾 Save the spoken content as an `audiobook.mp3`
- 🖥️ Simple terminal interface

### 1. Clone the Repository or Download the Code
    ```bash
    git clone https://github.com/your-username/pdf-to-audio-book.git
    cd pdf-to-audio-book
### 2. Install Required Libraries
          
    pip install pyttsx3 PyPDF2 gTTS

### 3. Run the Script
     
    python main.py

### 4. Choose an Option
Press 1 to listen to the PDF content
Press 2 to save the content as an audiobook.mp3

⚠️ Notes
This tool only works with PDFs that contain text (not scanned images).

For image-based PDFs, OCR support can be added (ask if needed).
Output file (audiobook.mp3) is saved in the current directory.

💡 Idea
This project was built as a resume project to showcase Python and file handling skills. Great for beginners!
