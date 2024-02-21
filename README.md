# Say It in German!
A translation app that takes in English text and translates it to German, with the option of speaking it as well. It is built with HTML, CSS, JavaScript, Node.js, Express, and powered by OpenAI and Eleven Labs for TTS. 

![home-page](images/home-page.png "Home Page")

## In This Document:
- [Live Application URL](#live-application-url)
- [Repositories](#repositories)
- [How to Use the Application](#how-to-use-the-application)
- [Technologies Used](#technologies-used)
- [Future Features:](#future-features)
- [Challenges and Learning Points:](#challenges-and-learning-points)

## Live Application URL
https://sayitingerman.netlify.app/

## Repositories:
1. [UI Repository](https://github.com/shantdashjian/say-it-in-german-ui/blob/main/README.md).
2. [API Repository](https://github.com/shantdashjian/say-it-in-german-api).
   

## How to Use the Application
1. A traveller to Germany opens the app.
2. The traveller writes the phrase in English.
3. The traveller clicks on Translate.
4. The app should show the translation in English.
5. The traveller can click on the Speak button and the app should read the translation.
6. The traveller can click on Clear to clear the input area and start over.

## Technologies Used
1. HTML, CSS, and JavaScript.
2. Node.js and Express.
3. [OpenAI API](https://platform.openai.com/docs/introduction/overview) for the translation.
4. [Eleven Labs API](https://elevenlabs.io/docs/api-reference/text-to-speech) for the TTS (Text to Speech).
5. Progressive Web Apps methodology, using site.webmanifest file and icons.

## Future Features:
1. The traveller can speak English into the app and the app would capture it in writing and do the translation to German automatically. 

## Challenges and Learning Points:
1. I used Figma to design the UI.
2. Limiting the origin of the request using CORS options.
3. Initially I wanted to move both functionalities, the translate and the speak to the backend. The translate worked. Moving the speak didn't as the free tier of the hosting service apparently limits the size of the audio file sent back. It was fine to keep it in the frontend as I am using a free API key.   
<hr>

[Up](README.md)
