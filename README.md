# 🔰 RZtube: Transforming YouTube Videos into Quizzes with Streamlit

RZtube offers an innovative approach to create interactive quizzes from YouTube video captions. By extracting captions using the [`youtube-transcript-api`](https://github.com/jdepoix/youtube-transcript-api) and subsequently processing the text with OpenAI's LLM, `RZtube` serves as a powerful tool for enhancing video content interaction.


## How It Works

1. **Caption Extraction:** Using the [`youtube-transcript-api`], captions are extracted from a given YouTube video URL.
2. **Quiz Generation:** The extracted captions are then fed into OpenAI's LLM using [`LangChain Python`](https://python.langchain.com/) with a predefined prompt template. The model generates questions based on the content, turning the video's key points into an interactive quiz.
3. **Streamlit Integration:** The quizzes are seamlessly integrated and displayed in a Streamlit app, providing users with a unique and interactive experience.

## Feedback & Collaboration
For Support Email me on "r.zarrar77768@gmail.com" or "zarrarzafar123@gmail.com"