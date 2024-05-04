# Example AI as a Resume Candidate Expert

Provides an example of using Google's Gemini within a websocket application of [github.com/gorilla/websocket](https://github.com/gorilla/websocket).
This is loosely based off the chat client example [github.com/gorilla/websocket/blob/main/examples/chat](https://github.com/gorilla/websocket/blob/main/examples/chat).

## Thoughts on this example
* Given the latency of response and lack of continuing context I am probably better
* Not production ready:
  * No client rate limiting
  * No rate limits upstream to Google
  * Payloads should be shorter
  * Many security concerns.
