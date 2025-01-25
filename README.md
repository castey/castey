## Hello, friends! 👋

Hi, my name is **David Castro**. I am a 3rd-year student earning a **Bachelor of Science in Computer Science (BSCS)** at [Wright State University](https://www.wright.edu).

Two projects I am working on this semester are:

- 🤖 **A Facebook bot** I created this a few years ago using node.js, openai, and an unofficial [Facebook API](https://github.com/Schmavery/facebook-chat-api) and have been adding to ever since - I'm in the process of rewriting it because it was very badly thrown together and getting harder and harder to maintain. <br> Uses embeddings and cosine similarity to operate as a retrieval-augmented generation (RAG) model on top of GPT4, making it capable of having long term memory outside of its given context window. The retrieval is done just by interactng with a mysql database and brute forcing the cosine similarity comparisons, but eventually I'd like to use a better method like ANNOY. As this will become increasingly and eventually painfully inefficient. Embeddings are done with [TensorFlow universal sentence-encoder](https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder). I don't have the project in a public repo yet since Im building it off a fork of the Facebook API that includes mission critical fixes. Eventually I'll get around to uploading it standalone.

- 🛠️ **An Arduino robot** that I'm gonna connect to OpenAI's API. I tried connecting some motors to a power supply module connected to the arduino but I think I killed the capacitor on the power supply so I guess I need to brush up on my circuit analysis physics.
