#  📚 Feeling analyzer

Hi,
I'm Yoann, I'm currently deepening my knowledge in web development. I'm specialized in React frontend development.
I had fun coding all these projects!
Don't hesitate if you have any questions, and have a look at my other projects ;)
Have fun coding!

## ✍️ Description 

The objective of this challenge is to build an application able to analyze a sentence typed by a user (in English only) and to determine its sentiment

(happy, angry or neutral) thanks to a third-party service: the NodeJS sentiment module.

According to the determined sentiment, your application will have to look like one of these three models (in order: happy, angry, neutral).

The objective of this challenge is to build an application that can analyze a sentence entered by a user (in English only) and determine its sentiment (happy, angry or neutral) using a third-party service: the NodeJS sentiment module.

Depending on the sentiment determined, your application should resemble one of these three mockups (in order: happy, angry, neutral).

Build your backend by integrating the sentiment module. Create a POST /analyze route that, based on the message entered in the input, returns the following:

- The result of the route (result is true if req.body.message is valid and the sentiment module has returned a response, otherwise false).
- The score returned by the sentiment module if the result is true.

From the frontend, in the script.js file, create a request to the backend that runs as soon as a character is entered in the input with the id "message" to receive the corresponding score.

Depending on the received score, you must modify the background color, the description (id="feeling"), the image (id="sentiment") and the score (id="score"), according to the following conditions:

- score < 0: #EC7C89, ANGRY, angry.png, and the score value.
- score = 0: #82C0CC, NEUTRAL, neutral.png, and the score set to 0.
- score > 0: #F5DA7D, HAPPY, happy.png, and the score value.
- empty input: #FFFFFF, empty description, question-mark.png, and the score set to 0.

This project is intended for beginner developers.

## 🎬 Getting Started : Dependencies and Other

!! Be careful, all my projects have a separate backend and frontend, you will find them here on my github.

```

yarn insall

```

Sentiment : [https://www.npmjs.com/package/sentiment](https://www.npmjs.com/package/sentiment)

## 🚀 Deploy 

⇒ [https://feelinganalyzer-frontend.vercel.app/](https://feelinganalyzer-frontend.vercel.app/)

Vercel : [https://vercel.com/](https://vercel.com/)

## 🧑‍💻 Authors

Yoann Drx, Paris, France 

## 🌐 Network

LinkedIn : [https://www.linkedin.com/feed/](https://www.linkedin.com/feed/)
