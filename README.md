# Qdrant_for_everyone
<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=40&pause=1000&color=F52828&center=true&vCenter=true&width=600&lines=Welcome+to+Qdrant_for_everyone;The+Easiest+Way+to+Learn+Vector+Search;Beginner+Friendly+%7C+Open+Source+%7C+Fast" alt="Typing SVG" />
<img src="https://qdrant.tech/images/logo_with_text.png" width="500" alt="Qdrant Logo">

<br/><br/>

<a href="https://github.com/bxbee/Qdrant_for_everyone">
  <img src="https://img.shields.io/github/stars/bxbee/Qdrant_for_everyone?style=for-the-badge&color=blue" alt="Stars">
</a>
<a href="https://github.com/bxbee/Qdrant_for_everyone/fork">
  <img src="https://img.shields.io/github/forks/bxbee/Qdrant_for_everyone?style=for-the-badge&color=orange" alt="Forks">
</a>
<a href="https://github.com/bxbee/Qdrant_for_everyone/issues">
  <img src="https://img.shields.io/github/issues/bxbee/Qdrant_for_everyone?style=for-the-badge&color=red" alt="Issues">
</a>
<a href="https://opensource.org/licenses/MIT">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT">
</a>

<br/>

<h3>🚀 Master Vector Databases with Zero Experience Needed!</h3>

[**Explore Docs**](https://qdrant.tech/documentation/) | [**Watch Tutorials**](#-video-guides) | [**Report Bug**](https://github.com/bxbee/Qdrant_for_everyone/issues)

</div>

---

## 📖 About The Project

**Qdrant_for_everyone** is designed to demystify Vector Search. Whether you are a student, a hobbyist, or a developer looking to integrate AI search into your app, this repo provides the building blocks you need.

### Why Qdrant?
* **Fast & Scalable:** Built in Rust for high performance.
* **Easy API:** Simple HTTP and gRPC interfaces.
* **AI Ready:** Perfect for RAG (Retrieval Augmented Generation), Semantic Search, and Recommendation Systems.

<div align="center">
  <img src="[https://opendatascience.com/wp-content/uploads/2022/10/LH2.png]">
  <br>
  <i>(Visualizing how Vector Search finds similar items instantly)</i>
</div>

---

## 🛠️ Tools & Tech Stack

We use the best open-source tools to make this happen:

| Core | Language | Containerization | 
| :---: | :---: | :---: |
| <img src="https://qdrant.tech/images/logo.svg" width="50" alt="Qdrant"> <br> **Qdrant** | <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="50" alt="Python"> <br> **Python** | <img src="https://www.docker.com/wp-content/uploads/2022/03/vertical-logo-monochromatic.png" width="50" alt="Docker"> <br> **Docker** |

---

## 🏁 Getting Started (Step-by-Step)

Follow these steps to get your own vector search engine running in minutes.

### Prerequisites
* Docker installed on your machine.
* Python 3.8+

### Step 1: Clone the Repo
```bash
git clone [https://github.com/bxbee/Qdrant_for_everyone.git](https://github.com/bxbee/Qdrant_for_everyone.git)
cd Qdrant_for_everyone
```
Step 2: Run Qdrant with DockerWe use Docker to spin up the Qdrant server instantly.Bashdocker pull qdrant/qdrant
docker run -p 6333:6333 qdrant/qdrant
<div align="center"><img src="https://www.google.com/search?q=https://placehold.co/600x200/222/FFF%3Ftext%3DScreenshot:%2BDocker%2BTerminal%2BOutput" alt="Docker Running"></div>Step 3: Install Python ClientBashpip install qdrant-client
Step 4: Run Your First SearchCheck the examples/ folder for the basic_search.py script.Pythonfrom qdrant_client import QdrantClient
from qdrant_client.models import PointStruct

client = QdrantClient(host="localhost", port=6333)
print("Qdrant is running!")
📺 Video GuidesClick the images below to watch the step-by-step video tutorials on YouTube.1. Installing Qdrant2. Your First Collection3. Semantic Search DemoSetting up Docker & EnvironmentCreating Points & VectorsBuilding a Movie RecommenderNote 🌟 Features & UsesHere is what you can build with this repository:🔍 Semantic Search: Search by meaning, not just keywords (e.g., searching "scary movie" finds "The Shining").🛍️ Recommendation System: "Users who bought X also liked Y."🤖 Chatbot Memory: Give your LLMs (like GPT) long-term memory.🖼️ Image Search: Upload a photo to find similar photos.<div align="center"><img src="https://www.google.com/search?q=https://placehold.co/800x300/1e1e2e/FFF%3Ftext%3DDiagram:%2BHow%2BEmbeddings%2BWork" alt="Embedding Diagram"></div>🤝 ContributingContributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.Fork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingFeature)Commit your Changes (git commit -m 'Add some AmazingFeature')Push to the Branch (git push origin feature/AmazingFeature)Open a Pull Request<div align="center">Show your support!Give a ⭐️ if this project helped you!<small>Maintained by <a href="https://www.google.com/search?q=https://github.com/bxbee">Raj Ghosh</a></small></div>
