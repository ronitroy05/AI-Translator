AI TRANSLATOR

This project is an AI-powered language translation application that leverages advanced machine learning models to provide accurate translations and corresponding pronunciations. Developed using Python, it integrates several key libraries and technologies to deliver a seamless user experience.

Key Components:

Gradio Interface: The application utilizes Gradio to create an intuitive web-based interface. Users can input the text they wish to translate and select their desired target language from a dropdown menu. Gradio facilitates the rapid deployment of this interactive interface, making the application accessible directly from a web browser.

Ollama's LLaMA 3.2 Model: At the core of the translation process is Ollama's LLaMA 3.2 model, a state-of-the-art language model known for its proficiency in handling multiple languages. The model is employed to perform translations while maintaining the original text's meaning, tone, and context. The application ensures that the latest version of the model is used by executing the command ollama pull llama3.2:latest.

Google Text-to-Speech (gTTS): To enhance user experience, the application incorporates gTTS for converting translated text into speech. This feature allows users to hear the pronunciation of the translated text. The application first checks if gTTS supports the selected target language; if supported, it generates an audio file of the translation. If not, it notifies the user that text-to-speech is unavailable for the chosen language.

Supported Languages:

The application currently supports translation and pronunciation for the following languages:

English
Hindi
French
Spanish
Japanese
These languages are mapped to their respective ISO language codes to ensure compatibility with the gTTS library.

Functionality:

Upon receiving user input, the application constructs a prompt that instructs the LLaMA 3.2 model to perform an accurate translation into the selected target language. The model processes this prompt and returns the translated text. If the target language is supported by gTTS, the application generates an audio file of the translated text, allowing users to listen to the pronunciation. The translated text and the audio file (if available) are then displayed on the Gradio interface.

Error Handling:

The application includes error handling mechanisms to manage potential issues during the translation and text-to-speech processes. If an error occurs, the application returns a message indicating the nature of the error, ensuring that users are informed of any issues that may arise.

Conclusion:

This project exemplifies the integration of advanced language models and user-friendly interfaces to create a practical tool for language translation and pronunciation. By combining Gradio, Ollama's LLaMA 3.2 model, and gTTS, the application offers users an efficient and accessible means to translate text and hear its pronunciation in multiple languages.
