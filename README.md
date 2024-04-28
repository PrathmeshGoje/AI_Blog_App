# AI_Blog_App
This application is a powerful tool that uses artificial intelligence to generate blog posts from YouTube video links.

## Features
- **YouTube Video to Blog Post**: Just provide a YouTube video link and the application will generate a comprehensive blog post.
- **Django Framework**: The application is built on the robust and secure Django web framework, ensuring high performance and security.
- **Gemini API**: The Gemini API is used for transcribing the YouTube video content, ensuring accurate and high-quality transcriptions.
- **AssemblyAI API**: The AssemblyAI API is used for natural language processing and understanding, enabling the application to generate meaningful and engaging blog content.
- **Blog Post Storage**: All generated blog posts are saved in a PostgreSQL database, allowing them to be accessed at any time.

## How it works
1. **Input**: The user inputs a YouTube video link.
2. **Transcription**: The AssemblyAI API processes the transcribed text and generates a well-structured and engaging blog post.
3. **Content Generation**: The Gemini API transcribes the video content into text.

This application is perfect for content creators, bloggers, and anyone interested in leveraging AI for content generation. Feel free to explore the code, raise issues, and contribute. Enjoy blogging with AI!

# Adding API Keys

This application uses the Gemini and AssemblyAI APIs, which require API keys. Follow these steps to add your API keys:

1. **Gemini API Key**:
   - Sign up or log in to your account on the Gemini website.
   - Navigate to the API section and generate a new API key.
   - Copy the API key.
   - Open the `views.py` file in the Django project.
   - Find the line that says `GEMINI_API_KEY = 'your_gemini_api_key'`.
   - Replace `'your_gemini_api_key'` with your actual Gemini API key enclosed in quotes.

2. **AssemblyAI API Key**:
   - Sign up or log in to your account on the AssemblyAI website.
   - Navigate to the API section and generate a new API key.
   - Copy the API key.
   - Open the `views.py` file in the Django project.
   - Find the line that says `ASSEMBLY_API_KEY = 'your_assembly_api_key'`.
   - Replace `'your_assembly_api_key'` with your actual AssemblyAI API key enclosed in quotes.

**Note**: Never share your API keys with anyone and do not commit them to version control. Consider using environment variables or Django's `secrets` module to keep your keys secure.

# Technologies Used
1. **Python**: The application is written in Python, a powerful, flexible, and beginner-friendly programming language.
2. **Django**: Django, a high-level Python web framework, is used for the backend of the application.
3. **Gemini API**: This API is used for transcribing the YouTube video content.
4. **AssemblyAI API**: This API is used for natural language processing and understanding.
5. **HTML**: HTML is used for structuring the web pages in the application.
6. **JavaScript**: JavaScript is used for adding interactivity to the web pages.
7. **Tailwind CSS**: Tailwind CSS, a utility-first CSS framework, is used for styling the web pages.
8. **PostgreSQL**: PostgreSQL, a powerful, open-source object-relational database system, is used for data storage.




   
