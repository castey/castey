## Hello, friends! 👋

Hi, my name is **David Castro**. I am a 3rd-year computer science student earning a **Bachelor of Science (BSCS)** at [Wright State University](https://www.wright.edu).

Some projects I am working on this semester are:

- 🔬 **Independent Study Project Investigating drift in knowledge graph embeddings**:<br>[An independent study I'm doing](https://github.com/castey/KGE-IS). Also working on a RAG bot using knowledge graphs and small language models.

- 🤖 **A Facebook bot**:<br>I created this a few years ago using node.js, openai, and an unofficial [Facebook API](https://github.com/Schmavery/facebook-chat-api) and have been adding to it ever since - I'm in the process of rewriting it because it was very badly thrown together and got harder and harder to maintain.<br><br>Uses embeddings and cosine similarity to operate as a retrieval-augmented generation (RAG) model on top of GPT4, making it capable of having long term memory outside of its given context window. The retrieval is done just by interactng with a mysql database and brute forcing the cosine similarity comparisons, but eventually I'd like to use a better method like ANNOY. As this will become increasingly and eventually, painfully inefficient.<br><br>Embeddings are done with [TensorFlow Universal Sentence Encoder](https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder). I don't have the project in a public repo yet since I'm building it off a private fork of the Facebook API that includes mission critical fixes by [robertlockesoftware](https://github.com/robertlockesoftware). Eventually I'll get around to uploading it standalone.

- 💻 **RAG bot using semantic embeddings and GPT-4**:<br>This is just the RAG portion of the Facebook bot.

- 🛠️ **An Arduino robot**:<br>I'm gonna connect this to OpenAI's API and my RAG system. I tried connecting some motors to a power supply module connected to the arduino but I think I killed the capacitor on the power supply so I guess I need to brush up on my circuit analysis physics. (Ok I haven't been giving this one much attention, maybe over the summer)
