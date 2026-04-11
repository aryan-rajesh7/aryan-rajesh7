# Hello, I'm Aryan Rajesh 👋

I am a Computer Science student at UC Irvine with a strong focus on architecting end-to-end AI applications and agents. I build full-stack systems that connect real-time data ingestion pipelines, machine learning inference, and LLM reasoning chains into cohesive, scalable production environments.

---

## 🛠️ Technical Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python (3.11), TypeScript, JavaScript, C++, C#, Java, HTML, CSS, SQL |
| **Machine Learning & AI** | PyTorch, XGBoost, ONNX, scikit-learn, NumPy, pandas, Google Gemma 3.0, RAG, LangChain |
| **Backend** | FastAPI, Uvicorn, Celery, Redis, pybind11, WebSockets |
| **Frontend** | Next.js 14, React 18, Tailwind CSS, MapLibre GL JS |
| **DevOps & Cloud** | Docker, GitHub Actions (CI/CD), Vercel, Hugging Face Spaces, Render, Koyeb |
| **Data & APIs** | REST APIs, TomTom Flow API, Nominatim Geocoding, OpenStreetMap |

---

## 🚀 Featured Projects

### AI Traffic Signal Optimizer
> A real-time, full-stack predictive modeling and GIS platform designed to optimize urban street-level vehicle flow.

* **Architecture:** Built a highly asynchronous FastAPI backend that ingests live TomTom API telemetry and pushes it to a Next.js frontend via persistent WebSockets.
* **Machine Learning:** Engineered a dual-model pipeline using a PyTorch LSTM for time-series forecasting and an XGBoost regressor for tabular feature importance to predict congestion volatility.
* **Reasoning Engine:** Implemented a fully stateless Retrieval-Augmented Generation (RAG) pipeline using Google Gemini Gemma 3 to generate live, human-readable signal timing recommendations based on real-time street conditions.
* **Performance:** Developed a C++ `pybind11` extension module for high-speed computation and deployed the system across Vercel and Render.

### Nexus + Lex3D Suite
> An offline, cross-modal generative AI framework engineered for local execution on Apple Silicon.

* **Hardware Acceleration:** Configured a custom PyTorch environment utilizing the Metal Performance Shaders (MPS) backend to execute heavy matrix multiplications directly on consumer GPU hardware.
* **Nexus Pipeline:** Chained multiple diffusion models (Stable Diffusion v1.5, Stable Video Diffusion, AudioLDM) to generate synchronized 2D, video, and audio outputs from semantic text prompts.
* **Lex3D Generation:** Utilized OpenAI's Shap-E to generate Implicit Neural Radiance Fields (NeRFs), converting text prompts into 3D latent space and exporting them as standardized, CAD-compatible STL meshes via `Trimesh`.
* **Memory Management:** Implemented rigorous VRAM clearing and CPU offloading (`enable_sequential_cpu_offload`) to prevent memory leaks during iterative inference steps.

---

## 📫 Let's Connect

* **LinkedIn:** [Aryan Rajesh](https://www.linkedin.com/in/aryan-rajesh7)
* **Hugging Face:** [@aryan-rajesh7](https://huggingface.co/aryan-rajesh7)
* **Portfolio:** [aryan-rajesh-portfolio.vercel.app](https://aryan-rajesh-portfolio.vercel.app/)
