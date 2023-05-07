# openai-examples
Contains the sample OpenAI projects

### Prerequisites
Node js must be install. Check is nodejs is installed or not
`node -v`

### How run this this project?

Clone the repo `https://github.com/RajkumarPR/openai-examples.git`

The repopsitory contains the **client** and **server** modules. Install the `node_modules`.
```
cd client
npm install
npm run dev #run the client module
```
Repeat same command to for server module
```
cd .. #come out of the client module
cd server
npm install
```
Before running server module, create `.env` file add the OpenAI API key
```
OPENAI_API_KEY="your api key"
```
Then run the server module
```
npm run server
```
Once the client and server started successfully open the below url in the browser

http://localhost:5173/

I have followed the below youtube video.

https://www.youtube.com/watch?v=2FeymQoKvrk&list=LL&index=1&t=3188s
