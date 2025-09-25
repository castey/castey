# Hello, friends! 👋

Hi, my name is **David Castro**. I am a 3rd-year computer science student earning a **Bachelor of Science (BSCS)** at [Wright State University](https://www.wright.edu) with a minor in psychology.

President of the [Society for Hispanic Professional Engineers](https://wright.campuslabs.com/engage/organization/society-of-hispanic-professional-engineers) at Wright State and Treasurer of a new student organization, the Wright State Chess Club

## Fall Semester Projects 

### KastleLab Projects

Projects related to the [Knowledge and Semantic Technologies Laboratory](https://kastle.cs.wright.edu/) at Wright State University. 

- [Representing knowledge graph entities and outputting a knowledge graph of that processed representation.](https://github.com/castey/CodeForKastle/windower)

- [Downloading scientific papers programmatically from various publications.](https://github.com/castey/CodeForKastle/paper-scraper)

### Extracurriculars
- [Project to turn the stairs in the atrium of the Russ Engineering Building into a piano staircase.](https://github.com/BoffinFactory/PianoStaircase)

### Coursework

- CEG-4110 Intro to Software Engineering: web application to determine graduation timelines given some major/minor and co-op options. (private repo)

- CEG-3310 Computer Organization: LC-3 assembly.

- EGR-3350 Technical Communications for Engineers and Computer Scientists.

- CS-2210 Logic for Computer Scientists.

- STT-3700 Intro to Statisical Inference: calculus based stats class.

## Past Projects:

### 🔬 [Independent Study Project Investigating drift in knowledge graph embeddings](https://github.com/castey/KGE-IS) 
Measured embedding drift between triples, using TransE with a fixed seed for reproducibility, on the FB15k-237, FB15k-238, and FB15k-239 datasets. Generated plots and visualizations using pyplot, t-SNE, and UMAP.

### 🤖 [Facebook bot](https://github.com/castey/facebook-chat-bot)
I created this a few years ago using node.js, openai, and an unofficial [Facebook API](https://github.com/Schmavery/facebook-chat-api) and have been adding to it ever since - I'm in the process of rewriting it because it was very badly thrown together and got harder and harder to maintain.<br><br>Uses embeddings and cosine similarity to operate as a retrieval-augmented generation (RAG) model on top of GPT4, making it capable of having long term memory outside of its given context window. The retrieval is done just by interactng with a mysql database and brute forcing the cosine similarity comparisons, but eventually I'd like to use a better method like ANNOY. As this will become increasingly and eventually, painfully inefficient.<br><br>Embeddings are done with [TensorFlow Universal Sentence Encoder](https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder). I don't have the project in a public repo yet since I'm building it off a private fork of the Facebook API that includes mission critical fixes by [robertlockesoftware](https://github.com/robertlockesoftware). Eventually I'll get around to uploading it standalone.

### 💻 [RAG bot using semantic embeddings and GPT-4](https://github.com/castey/ragBot)

RAG portion of the Facebook bot.

### 🛠️ An Arduino robot
Learned some fundamentals of arduinos
