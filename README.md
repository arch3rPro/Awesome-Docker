# Awesome Docker[![Awesome](https://camo.githubusercontent.com/3418ba3754faddfb88c5cbdc94c31ad670fc693c8caa59bc2806c9836acc04e4/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://awesome.re/)

[中文](README_ZH.md) | [English](README.md)

This is a collection of Docker resources designed to help developers, operators, and technical teams better use Docker technology. This project covers a full range of resources from introductory tutorials to advanced practices, including official documentation, management tools, security guides, best practices, etc. Whether you are a Docker beginner or an experienced expert, you can find valuable tools and references here to help improve the efficiency of containerized development and deployment.

![Banner](./Banner.png)

## Table of contents

- [Official Resources](https://github.com/arch3rPro/Awesome-Docker#官方资源)
- [tool](https://github.com/arch3rPro/Awesome-Docker#工具)
- [Tutorial](https://github.com/arch3rPro/Awesome-Docker#教程)
- [Best Practices](https://github.com/arch3rPro/Awesome-Docker#最佳实践)
- [Security](https://github.com/arch3rPro/Awesome-Docker#安全性)
- [monitor](https://github.com/arch3rPro/Awesome-Docker#监控)
- [Orchestration and Clustering](https://github.com/arch3rPro/Awesome-Docker#编排和集群)
- [Image building](https://github.com/arch3rPro/Awesome-Docker#镜像构建)
- [Development Tools](https://github.com/arch3rPro/Awesome-Docker#开发工具)
- [Application Recommendation](https://github.com/arch3rPro/Awesome-Docker#应用推荐)
- [Contribution Guidelines](https://github.com/arch3rPro/Awesome-Docker#贡献指南)

## Official Resources

- [Docker official website](https://www.docker.com/) - Docker official website
- [Docker Hub](https://hub.docker.com/) - Docker's official image repository
- [Docker Docs](https://docs.docker.com/) - Official Docker documentation
- [Docker GitHub](https://github.com/docker) - Docker's GitHub organization
- [Docker Blog](https://www.docker.com/blog/) - Docker official blog

## Management Tools

- [Portainer](https://www.portainer.io/) - Powerful container management UI interface
- [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container Docker applications
- [Dive](https://github.com/wagoodman/dive) - A tool for exploring Docker image layers.
- [Lazydocker](https://github.com/jesseduffield/lazydocker) - A terminal UI for Docker
- [ctop](https://github.com/bcicen/ctop) - top-like monitoring tool for containers

## Tutorial

- [Docker - From Getting Started to Practice](https://yeasy.gitbook.io/docker_practice/) - Chinese Docker Practice Guide
- [Docker Curriculum](https://docker-curriculum.com/) - Learn Docker from scratch
- [Play with Docker](https://labs.play-with-docker.com/) - Online Docker Lab

## Best Practices

- [Docker Best Practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/) - The official Dockerfile best practices guide
- [Container](http://docs.projectatomic.io/container-best-practices/) Best Practices
- [Docker Security Best Practices](https://snyk.io/blog/10-docker-image-security-best-practices/) - Docker Image Security Best Practices

## Security

- [Docker Bench Security](https://github.com/docker/docker-bench-security) - Docker host security check script
- [Clair](https://github.com/quay/clair) - Static Analysis of Container Vulnerabilities
- [Trivy](https://github.com/aquasecurity/trivy) - A simple yet comprehensive container vulnerability scanner

## Container Monitoring

- [cAdvisor](https://github.com/google/cadvisor) - container resource usage and performance analysis
- [Prometheus](https://prometheus.io/) - Open Source Monitoring Solution
- [Grafana](https://grafana.com/) - Monitoring data visualization

## Orchestration and Clustering

- [Kubernetes](https://kubernetes.io/) - Container Orchestration Platform
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - Docker native clustering tool
- [Rancher](https://rancher.com/) - Enterprise-grade container management platform

## Image building

- [BuildKit](https://github.com/moby/buildkit) - The next generation Docker image building tool
- [Kaniko](https://github.com/GoogleContainerTools/kaniko) - Building container images in Kubernetes
- [Multi-stage](https://docs.docker.com/develop/develop-images/multistage-build/) builds

## Development Tools

- [Docker VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) - Docker extension for VS Code
- [Docker Desktop](https://www.docker.com/products/docker-desktop) - Desktop Docker development environment
- [Telepresence](https://www.telepresence.io/) - Tool for local development of Kubernetes services

## Application Recommendation

### 🧠 AI Applications

#### 💬 LLM Client

| name               | type                  | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------------ | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Lobe Chat          | Private deployment    | An open source, modern AI chat framework. Supports multiple AI providers | [lobehub/lobe-chat](https://github.com/lobehub/lobe-chat)    | 57.4k        | 1M+          |
| Be                 | Model Run             | A framework for running large language models such as Llama 2 locally | [to be/to be](https://github.com/ollama/ollama)              | 42.3k        | 10M+         |
| Open WebUI         | Interactive interface | A scalable, feature-rich, and user-friendly self-hosted AI platform designed to run completely offline | [open-webui/open-webui](https://github.com/open-webui/open-webui) | 82k          | 10M+         |
| LocalAI            | Local Inference       | Locally running AI server, compatible with OpenAI API, supports multiple models | [go-skynet/LocalAI](https://github.com/go-skynet/LocalAI)    | 15.2k        | 20M+         |
| LM Studio          | Model Management      | A local large language model exploration and reasoning tool that supports a variety of open source models | [lmstudio-ai/lmstudio](https://github.com/lmstudio-ai/lmstudio) | 8.5k         | 5M+          |
| Text Generation UI | Interactive interface | Web UI for large language models, supporting multiple models and parameter adjustments | [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) | 28.7k        | 15M+         |
| LangChain          | Development Framework | LLM application development framework, supporting chain calls and tool integration | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 72.5k        | 25M+         |
| Flowise            | Workflow Tools        | Drag-and-drop LangChain application building tool, no coding required | [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise)    | 18.9k        | 10M+         |
| LlamaIndex         | Data Frame            | Dataframes that connect custom data to large language models | [jerryjliu/llama_index](https://github.com/jerryjliu/llama_index) | 25.6k        | 8M+          |
| Jan                | Local Assistant       | A locally-run AI assistant that supports multiple open source models | [janhq/jan](https://github.com/janhq/jan)                    | 12.8k        | 5M+          |
| PrivateGPT         | Private deployment    | A framework for interacting with LLM using private documents to protect data privacy | [imartinez/privateGPT](https://github.com/imartinez/privateGPT) | 45.2k        | 12M+         |

#### 🤖 Machine Learning

| name               | type                  | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------------ | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| MLflow             | Model Management      | An open source machine learning lifecycle platform that supports experiment tracking and model deployment | [mlflow/mlflow](https://github.com/mlflow/mlflow)            | 15.8k        | 100M+        |
| Kubeflow           | ML Platform           | A Kubernetes-based machine learning toolkit for model development and deployment | [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow)    | 13.2k        | 50M+         |
| TensorFlow Serving | Model Serving         | TensorFlow's official model deployment system supports model version management | [tensorflow/serving](https://github.com/tensorflow/serving)  | 5.8k         | 500M+        |
| Seldon Core        | Inference Engine      | Production-grade machine learning model deployment platform, supporting multiple frameworks | [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core) | 3.8k         | 20M+         |
| BentoML            | Model deployment      | A framework for building and deploying machine learning services | [bentoml/BentoML](https://github.com/bentoml/BentoML)        | 5.2k         | 10M+         |
| Polyaxon           | ML Platform           | Machine learning experiment management and model deployment platform | [polyaxon/polyaxon](https://github.com/polyaxon/polyaxon)    | 3.5k         | 5M+          |
| DVC                | Version Control       | Data version control and machine learning experiment management tools | [iterative/dvc](https://github.com/iterative/dvc)            | 12.2k        | 15M+         |
| Ray                | Distributed Framework | A framework for building distributed machine learning applications | [ray-project/ray](https://github.com/ray-project/ray)        | 28.5k        | 50M+         |
| Feast              | Feature storage       | Machine learning feature storage, supporting online and offline feature management | [feast-dev/feast](https://github.com/feast-dev/feast)        | 4.2k         | 5M+          |

#### 🗣️ Natural Language Processing

| name         | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------ | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Hugging Face | NLP Platform        | The most popular natural language processing model library and platform, providing thousands of pre-trained models | [huggingface/transformers](https://github.com/huggingface/transformers) | 115k         | 200M+        |
| spaCy        | NLP Framework       | Industrial-grade natural language processing library, supporting multiple languages and tasks | [explosion/spaCy](https://github.com/explosion/spaCy)        | 27.5k        | 100M+        |
| NLTK         | NLP Toolkit         | A classic Python library for natural language processing, providing a variety of text processing functions | [nltk/nltk](https://github.com/nltk/nltk)                    | 12.8k        | 50M+         |
| Rasa         | Dialogue System     | An open source conversational AI framework for building chatbots and voice assistants | [RasaHQ/rasa](https://github.com/RasaHQ/rasa)                | 16.5k        | 100M+        |
| Gensim       | Text Analysis       | Topic modeling and document similarity analysis library suitable for large-scale text processing | [RaRe-Technologies/gensim](https://github.com/RaRe-Technologies/gensim) | 14.2k        | 20M+         |
| FastText     | Text Classification | Efficient text classification and word embedding library developed by Facebook | [facebookresearch/fastText](https://github.com/facebookresearch/fastText) | 24.8k        | 10M+         |
| StanfordNLP  | NLP Toolkit         | Stanford University developed a natural language processing toolkit that supports multiple languages | [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza)  | 6.8k         | 5M+          |
| AllenNLP     | NLP Platform        | A natural language processing research library based on PyTorch | [allenai/allennlp](https://github.com/allenai/allennlp)      | 11.5k        | 10M+         |
| Flair        | NLP Framework       | A simple and easy-to-use NLP framework focusing on sequence labeling and text classification | [flairNLP/flair](https://github.com/flairNLP/flair)          | 13.2k        | 5M+          |

#### 👁️ Computer Vision

| name          | type             | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| OpenCV        | Visual Library   | The most popular computer vision library, supporting a variety of image processing and vision algorithms | [opencv/opencv](https://github.com/opencv/opencv)            | 72.5k        | 500M+        |
| Detectron2    | Object Detection | Facebook's object detection and segmentation framework, based on PyTorch | [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) | 27.8k        | 50M+         |
| YOLO          | Object Detection | Real-time target detection system with fast speed and high accuracy | [ultralytics/yolov5](https://github.com/ultralytics/yolov5)  | 45.2k        | 100M+        |
| MMDetection   | Vision Toolbox   | OpenMMLab developed a target detection toolbox that supports multiple detection algorithms | [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) | 25.8k        | 20M+         |
| DeepLabCut    | Pose Estimation  | A deep learning toolbox for animal pose estimation           | [DeepLabCut/DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) | 3.8k         | 5M+          |
| EasyOCR       | Text Recognition | OCR system supporting more than 80 languages, easy to use    | [JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)      | 19.5k        | 30M+         |
| Tesseract OCR | Text Recognition | OCR engine developed by Google, supports multiple languages and formats | [tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract) | 52.8k        | 200M+        |
| Deepface      | Face Analysis    | A lightweight face recognition and analysis library that supports a variety of deep learning models | [Serengil/deepface](https://github.com/serengil/deepface)    | 8.5k         | 10M+         |
| ImageAI       | Vision AI        | An easy-to-use computer vision Python library that supports image prediction and detection | [Olafenwa Moses/ImageAI](https://github.com/OlafenwaMoses/ImageAI) | 7.8k         | 5M+          |

#### 🔧 AI Development Tools

| name             | type                     | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------------- | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| TensorFlow       | Deep Learning Frameworks | Google's end-to-end open source machine learning platform    | [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) | 178k         | 1B+          |
| PyTorch          | Deep Learning Frameworks | Flexible deep learning framework developed by Facebook, research-friendly | [pytorch/pytorch](https://github.com/pytorch/pytorch)        | 72.5k        | 500M+        |
| Jupyter          | Interactive Development  | An interactive computing environment that supports multiple programming languages | [jupyter/docker-stacks](https://github.com/jupyter/docker-stacks) | 7.8k         | 1B+          |
| Streamlit        | Application Development  | A framework for quickly building and sharing data science and machine learning applications | [streamlit/streamlit](https://github.com/streamlit/streamlit) | 28.5k        | 100M+        |
| Gradio           | Interface construction   | A Python library for quickly creating user interfaces for machine learning models | [gradio-app/gradio](https://github.com/gradio-app/gradio)    | 21.2k        | 50M+         |
| ONNX             | Model exchange           | Open neural network exchange format, supporting multi-framework model conversion | [onnx/onnx](https://github.com/onnx/onnx)                    | 16.8k        | 100M+        |
| TensorRT         | Inference Optimization   | NVIDIA developed a high-performance deep learning inference optimizer | [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT)        | 8.5k         | 200M+        |
| Weights & Biases | Experiment tracking      | Machine learning experiment tracking and visualization tool  | [wandb/wandb](https://github.com/wandb/wandb)                | 6.2k         | 50M+         |
| DVC              | Data version control     | Data and model version control system for machine learning projects | [iterative/dvc](https://github.com/iterative/dvc)            | 12.2k        | 15M+         |

### 📽️ Media Management

#### 🎬 Video Server

| name      | type              | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Plex      | Integrated Server | Powerful streaming media server that supports management and streaming of multimedia content such as movies, TV series, and music | [plexinc/pms-docker](https://github.com/plexinc/pms-docker)  | 8.5k         | 6B+          |
| Jellyfin  | Integrated Server | Open source media system, a branch of Emby, completely free, supports real-time transcoding and multi-user management | [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin)    | 31.2k        | 800M+        |
| Emby      | Integrated Server | Professional media server, supporting live TV and DVR functions, providing excellent metadata scraping function | [emby/embyserver](https://github.com/MediaBrowser/Emby)      | 4.8k         | 150M+        |
| Navidrome | Music Server      | Modern music server supporting streaming and music library management | [navidrome/navidrome](https://github.com/navidrome/navidrome) | 9.2k         | 25M+         |

#### 🎵 Music playback

| name      | type             | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Mopidy    | Music Server     | Scalable music server supporting multiple music sources and playback protocols | [mopidy/mopidy](https://github.com/mopidy/mopidy)            | 8.8k         | 7M+          |
| Funkwhale | Music Server     | Modern music streaming server, supporting music sharing and social functions | [funkwhale/funkwhale](https://github.com/funkwhale/funkwhale) | 3.8k         | 1.5M+        |
| Airsonic  | Music Server     | Java-based music streaming server, supports multi-user and cross-platform | [airsonic/airsonic](https://github.com/airsonic/airsonic)    | 3.4k         | 12M+         |
| Volumio   | Audio System     | A system dedicated to high-quality music playback, supporting multiple audio formats | [volumio/volumio3](https://github.com/volumio/volumio3)      | 2.1k         | 800K+        |
| DeaDBeeF  | Audio Player     | High-quality audio player, supports multiple audio formats and plug-in extensions | [Deadbeef-Player/deadbeef-docker](https://github.com/DeaDBeeF-Player/deadbeef-docker) | 2.8k         | 150K+        |
| MPD       | Music Server     | Lightweight music player daemon, supports multiple client connections | [jcorporation/myMPD](https://github.com/jcorporation/myMPD)  | 1.5k         | 1.2M+        |
| Beets     | Music Management | Powerful music library management tool, supporting automatic tag and metadata management | [beetbox/beets](https://github.com/beetbox/beets)            | 12.1k        | 700K+        |
| LMS       | Music Server     | Logitech Media Server, which enables multi-room audio and smart home integration | [Logitech/slimserver](https://github.com/Logitech/slimserver) | 1.8k         | 250K+        |
| Gonic     | Music Server     | Lightweight Subsonic-compatible server that supports music streaming and playlists | [sentriz/gonic](https://github.com/sentriz/gonic)            | 1.5k         | 120K+        |

#### 📚 E-book management

| name        | type               | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Calibre-Web | General Management | An online e-book management system based on Calibre, supporting online reading, metadata editing and format conversion | [janeczku/calibre-web](https://github.com/janeczku/calibre-web) | 9.5k         | 50M+         |
| Kavita      | Comics Management  | Modern e-book and comic server, supporting multi-user and mobile access | [Kareadita/Kavita](https://github.com/Kareadita/Kavita)      | 3.8k         | 5M+          |
| Komga       | Comics Management  | A media server focused on comics and picture books, supporting series management and reading progress synchronization | [gotson/komga](https://github.com/gotson/komga)              | 2.9k         | 10M+         |
| COPS        | OPDS Service       | Lightweight Calibre OPDS server, supports online browsing and downloading of e-books | [seblucas/cops](https://github.com/seblucas/cops)            | 1.5k         | 1M+          |
| Ubooquity   | General Management | Multi-user media server for e-books and comics, with powerful metadata management | [vaemendis/ubooquity](https://github.com/vaemendis/ubooquity) | 2.2k         | 5M+          |
| Readarr     | E-book Automation  | Automatic download and management tool for e-books, supporting multiple download sources | [Readarr/Readarr](https://github.com/Readarr/Readarr)        | 2.8k         | 10M+         |
| LANraragi   | Comics Management  | An open source comic book manager that supports multiple formats and tag management | [Difegue/LANraragi](https://github.com/Difegue/LANraragi)    | 2.1k         | 3M+          |
| Calibre-RPC | Format Conversion  | Calibre's RPC server provides an API for converting e-book formats | [calibre-rest/calibre-rest](https://github.com/calibre-rest/calibre-rest) | 1.2k         | 500K+        |
| Stump       | Comics Management  | Modern comic and picture book server, supporting multiple users and reading progress synchronization | [aaronleopold/stump](https://github.com/aaronleopold/stump)  | 1.1k         | 200K+        |
| Tanoshi     | Comic Reading      | Self-hosted comic reading server, supports multiple comic sources and online reading | [faldez/tanoshi](https://github.com/faldez/tanoshi)          | 1.3k         | 100K+        |

#### 📸 Photo Management

| name        | type                     | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| PhotoPrism  | Photo library management | AI-based photo manager with facial recognition, geotagging and automatic categorization | [photoprism/photoprism](https://github.com/photoprism/photoprism) | 28.5k        | 100M+        |
| Immich      | Photo backup             | High-performance photo and video backup tool, supporting real-time backup on mobile devices | [immich-app/immich](https://github.com/immich-app/immich)    | 21.2k        | 10M+         |
| Lychee      | Album Sharing            | A simple and beautiful photo management system that supports online sharing and multi-user management | [LycheeOrg/Lychee](https://github.com/LycheeOrg/Lychee)      | 5.2k         | 10M+         |
| Pigallery2  | Album Management         | Fast photo and video browser with catalog scanning and metadata management | [bpatrik/pigallery2](https://github.com/bpatrik/pigallery2)  | 2.1k         | 1M+          |
| LibrePhotos | Photo library management | An open-source Google Photos alternative with facial recognition and automatic tagging | [LibrePhotos/librephotos](https://github.com/LibrePhotos/librephotos) | 5.8k         | 5M+          |
| Piwigo      | Album Sharing            | Feature-rich photo gallery system, plug-in extension and multi-language support | [Piwigo/Piwigo](https://github.com/Piwigo/Piwigo)            | 3.2k         | 10M+         |
| Chevereto   | Image hosting            | Professional image hosting and sharing platform, supporting multiple storage backends | [chevereto/chevereto](https://github.com/chevereto/chevereto) | 4.5k         | 5M+          |
| Photoview   | Photo browsing           | Simple and fast photo gallery, supports RAW format and geographic information display | [photoview/photoview](https://github.com/photoview/photoview) | 3.8k         | 1M+          |

#### 🎥 Video transcoding

| name      | type                  | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Jellyfin  | Transcoding Server    | Open source media system that supports real-time transcoding and hardware acceleration and can be used as an independent transcoding server | [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin)    | 28.3k        | 500M+        |
| HandBrake | Video Transcoding     | Powerful video transcoding tool that supports batch processing and custom presets | [HandBrake/HandBrake](https://github.com/HandBrake/HandBrake) | 16.8k        | 50M+         |
| FFmpeg    | Codec Tools           | The most popular audio and video processing framework, supporting transcoding and processing of almost all formats | [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg)            | 39.2k        | 2B+          |
| Tdarr     | Automatic transcoding | Distributed video transcoding system, supporting automated processing and health checks | [HaveAGitGat/Tdarr](https://github.com/HaveAGitGat/Tdarr)    | 2.8k         | 10M+         |
| Unmanic   | Automatic transcoding | Flexible folder monitoring and automatic transcoding tools, support plug-in extensions | [Unmanic/unmanic]( https://github.com/                       |              |              |

### 🤖 Automation Tools

#### ⬇️ Download the tool

| name                  | type                       | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------------------- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| qBittorrent           | BitTorrent Download        | Powerful BT download client, supports RSS subscription and WebUI | [linuxserver/qbittorrent](https://github.com/qbittorrent/qBittorrent) | 21.5k        | 500M+        |
| Transmission          | BitTorrent Download        | Lightweight BT client, supports web interface and remote control | [transmission/transmission](https://github.com/transmission/transmission) | 10.2k        | 300M+        |
| Aria2                 | Multi-protocol download    | A lightweight download tool that supports multiple protocols such as BT, HTTP and FTP | [aria2/aria2](https://github.com/aria2/aria2)                | 31.2k        | 200M+        |
| JDownloader           | Download from network disk | Download manager that supports multiple network disks and video sites | [jlesage/jdownloader-2](https://github.com/jlesage/docker-jdownloader-2) | 3.8k         | 100M+        |
| youtube-dl            | Video Download             | Command line download tool that supports multiple video sites | [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)            | 62.5k        | 50M+         |
| Syncthing             | File Sync                  | P2P file synchronization tool, supports real-time synchronization of multiple devices | [syncthing/syncthing](https://github.com/syncthing/syncthing) | 55.8k        | 150M+        |
| Deluge                | BitTorrent Download        | Feature-rich BT client, supports plug-in extensions          | [deluge/deluge](https://github.com/deluge/deluge)            | 4.5k         | 100M+        |
| pyLoad                | Download Management        | Download manager that supports multiple download sites       | [pyload/pyload](https://github.com/pyload/pyload)            | 3.2k         | 20M+         |
| Motrix                | Multi-protocol download    | A fresh and simple all-round download tool that supports multiple protocols | [agalwood/Motrix](https://github.com/agalwood/Motrix)        | 41.2k        | 10M+         |
| Free Download Manager | Multi-function download    | Full-featured download manager with multithreading support and browser integration | [freedownloadmanager/fdm](https://github.com/freedownloadmanager/fdm) | 2.8k         | 5M+          |

#### 📰 RSS aggregation

| name          | type             | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| FreshRSS      | RSS Reader       | A lightweight self-hosted RSS aggregator that supports multiple users and mobile access | [FreshRSS/FreshRSS](https://github.com/FreshRSS/FreshRSS)    | 7.2k         | 50M+         |
| Miniflux      | RSS Reader       | A minimalist feed reader with a focus on performance and security | [miniflux/v2](https://github.com/miniflux/v2)                | 5.8k         | 20M+         |
| RSS-Bridge    | RSS Generator    | Generate feeds for websites that do not provide RSS, supporting multiple mainstream websites | [RSS-Bridge/rss-bridge](https://github.com/RSS-Bridge/rss-bridge) | 6.2k         | 10M+         |
| RSSHub        | RSS Generator    | A generator for RSS feeds of all kinds, supporting hundreds of websites | [DIYgod/RSHub](https://github.com/DIYgod/RSSHub)             | 27.5k        | 100M+        |
| Tiny Tiny RSS | RSS Reader       | Feature-rich news reader that supports plugin extensions and theme customization | [tt-rss/tt-rss](https://github.com/tt-rss/tt-rss)            | 11.2k        | 30M+         |
| NewsBlur      | News Aggregation | Smart news reader that supports training personalized recommendations | [samuelclay/NewsBlur](https://github.com/samuelclay/NewsBlur) | 6.5k         | 5M+          |
| CommaFeed     | RSS Reader       | A simple and modern RSS reader similar to Google Reader      | [Athou/commafeed](https://github.com/Athou/commafeed)        | 2.8k         | 3M+          |
| Selfoss       | News Aggregation | A versatile news aggregator that supports multiple data sources and filters | [fossar/selfoss](https://github.com/fossar/selfoss)          | 2.5k         | 2M+          |
| Stringer      | RSS Reader       | Easy-to-use self-hosted RSS reader with Fever API support    | [stringer-rss/stringer](https://github.com/stringer-rss/stringer) | 3.8k         | 1M+          |
| Yarr          | RSS Reader       | Fast and lightweight feed reader with offline reading and full-text search support | [nkanaev/yarr](https://github.com/nkanaev/yarr)              | 2.1k         | 500K+        |

#### 🏠 Smart Home

| name           | type                 | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Home Assistant | Home Automation      | An open source smart home platform that supports thousands of device integrations and automation scenarios | [home-assistant/core](https://github.com/home-assistant/core) | 63k          | 100 million+ |
| Node-RED       | Automated processes  | Flow-based IoT programming tool that supports visual device linkage | [node-red/node-red](https://github.com/node-red/node-red)    | 17.8k        | 100 million+ |
| OpenHAB        | Intelligent Hub      | Multi-protocol smart home integration platform, supporting more than 2000 device types | [openhab/openhab-core](https://github.com/openhab/openhab-core) | 3.5k         | 50 million+  |
| Mosquitto      | MQTT Broker          | Lightweight message proxy server, supporting IoT device communication | [eclipse/mosquitto](https://github.com/eclipse/mosquitto)    | 7.2k         | 200 million+ |
| Zigbee2MQTT    | Protocol conversion  | A bridge tool that connects Zigbee devices to the MQTT ecosystem | [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt)  | 10.2k        | 30 million+  |
| ESPHome        | Device Management    | Quickly create IoT device firmware through YAML configuration | [esphome/esphome](https://github.com/esphome/esphome)        | 7.3k         | 20 million+  |
| Glances        | Resource Monitoring  | A cross-platform system monitoring tool that supports containerized deployment | [nicolargo/glances](https://github.com/nicolargo/glances)    | 25k          | 50 million+  |
| InfluxDB       | Time Series Database | A time series database designed specifically for IoT data    | [influxdata/influxdb](https://github.com/influxdata/influxdb) | 27k          | 100 million+ |
| Grafana        | Data Visualization   | Smart Home Data Dashboard Creation Tool                      | [grafana/grafana](https://github.com/grafana/grafana)        | 58k          | 300 million+ |
| Jeedom         | Intelligent Hub      | French open source smart home management system              | [jeedom/core](https://github.com/jeedom/core)                | 1.2k         | 10 million+  |
| Domoticz       | Home Automation      | Lightweight home automation system, supporting multiple protocols | [domoticz/domoticz](https://github.com/domoticz/domoticz)    | 3.5k         | 20 million+  |
| Homebridge     | Apple Ecosystem      | Connecting non-HomeKit devices to Apple smart home           | [homebridge/homebridge](https://github.com/homebridge/homebridge) | 23k          | 80 million+  |

#### 🕷️ Web crawler

| name       | type               | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Scrapy     | Crawler Framework  | A powerful Python crawler framework that supports distributed deployment and data pipelines | [scrapy/scrapy](https://github.com/scrapy/scrapy)            | 48.5k        | 50M+         |
| Crawlab    | Crawler Management | Distributed crawler management platform, supporting multiple programming languages and scheduled tasks | [crawlab-team/crawlab](https://github.com/crawlab-team/crawlab) | 10.2k        | 5M+          |
| Colly      | Crawler Framework  | A fast and elegant crawler framework written in Go           | [gocolly/colly](https://github.com/gocolly/colly)            | 20.5k        | 2M+          |
| Puppeteer  | Browser Automation | Chrome-based automation tool that supports page rendering and interaction | [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | 85.6k        | 100M+        |
| Selenium   | Browser Automation | Cross-platform Web automation testing tool that supports multiple browsers | [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) | 27.8k        | 200M+        |
| PhantomJS  | Headless browser   | A headless WebKit browser suitable for automated data collection | [ariya/phantomjs](https://github.com/ariya/phantomjs)        | 29.2k        | 50M+         |
| Pyspider   | Crawler Platform   | Python crawler system with web interface, supporting script editing and task monitoring | [binux/pyspider](https://github.com/binux/pyspider)          | 15.8k        | 3M+          |
| Playwright | Browser Automation | Modern web testing and automation framework that supports multiple browser cores | [microsoft/playwright](https://github.com/microsoft/playwright) | 58.2k        | 20M+         |

### 🛠️ DevOps

#### 🐳 Container Management

| name         | type                    | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------ | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Kubernetes   | Container Orchestration | Industry-standard container orchestration platform that provides automated deployment, expansion, and management | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | 102k         | -            |
| Docker Swarm | Container Orchestration | Docker native cluster management tool, simple configuration, suitable for small-scale deployment | [moby/swarmkit](https://github.com/moby/swarmkit)            | 6.2k         | -            |
| Portainer    | Container Management    | Intuitive Web UI management interface, supports Docker and Kubernetes | [portainer/portainer](https://github.com/portainer/portainer) | 26.5k        | 1B+          |
| Harbor       | Mirror repository       | Enterprise-level container image repository, supporting security scanning and access control | [goharbor/harbor](https://github.com/goharbor/harbor)        | 20.8k        | 10M+         |
| Prometheus   | Monitoring system       | Powerful monitoring and alarm system, providing rich container monitoring indicators | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k        | 1B+          |
| Consul       | Service Discovery       | Distributed service discovery and configuration management system | [hashicorp/consul](https://github.com/hashicorp/consul)      | 27.3k        | 100M+        |
| Rancher      | Container Platform      | A complete container management platform that supports multi-cluster management and application deployment | [rancher/rancher](https://github.com/rancher/rancher)        | 21.4k        | 500M+        |
| cAdvisor     | Resource Monitoring     | Container resource usage and performance analysis tools      | [google/cadvisor](https://github.com/google/cadvisor)        | 15.2k        | 1B+          |

#### 📊 Monitoring Alarm

| name          | type                   | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Prometheus    | Monitoring system      | The de facto standard for cloud-native monitoring systems, providing powerful data collection, storage, and query capabilities | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k        | 1B+          |
| Grafana       | Visualization Platform | A feature-rich indicator analysis and visualization platform that supports multiple data sources | [grafana/grafana](https://github.com/grafana/grafana)        | 58k          | 3B+          |
| Zabbix        | Enterprise Monitoring  | Enterprise-level distributed monitoring system, supporting multiple monitoring methods and alarm notifications | [zabbix/zabbix](https://github.com/zabbix/zabbix)            | 10k          | 500M+        |
| Nagios        | System Monitoring      | A long-established IT infrastructure monitoring system that provides comprehensive host and service monitoring | [NagiosEnterprises/nagioscore](https://github.com/NagiosEnterprises/nagioscore) | 3.5k         | 50M+         |
| Alertmanager  | Alarm Management       | Prometheus ecosystem alarm manager, supporting flexible alarm routing and notifications | [prometheus/alertmanager](https://github.com/prometheus/alertmanager) | 5.8k         | 500M+        |
| Netdata       | Real-time monitoring   | High-performance distributed real-time monitoring system with excellent visual interface | [netdata/netdata](https://github.com/netdata/netdata)        | 65k          | 2B+          |
| Elastic Stack | Log monitoring         | Powerful log collection and analysis platform, supporting complex data analysis and visualization | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k          | 1B+          |
| Sensu         | Monitoring framework   | Flexible monitoring and alarm framework, supporting automated operation and troubleshooting | [sensu/sensu-go](https://github.com/sensu/sensu-go)          | 4.2k         | 100M+        |

#### 📝 Log Analysis

| name          | type                   | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Elasticsearch | Log storage            | Distributed search and analysis engine, a core component of the ELK stack | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k          | 1B+          |
| Logstash      | Log Collection         | Server-side data processing pipeline capable of collecting data from multiple sources simultaneously | [elastic/logstash](https://github.com/elastic/logstash)      | 13.5k        | 500M+        |
| Kibana        | Log visualization      | Data visualization and exploration tool that provides a beautiful analysis interface for Elasticsearch | [elastic/kibana](https://github.com/elastic/kibana)          | 18.7k        | 500M+        |
| Fluentd       | Log Collection         | Unified log layer, an open source data collector that supports multiple input and output formats | [fluent/fluentd](https://github.com/fluent/fluentd)          | 12.3k        | 100M+        |
| Graylog       | Log Platform           | Centralized log management platform, providing powerful search functions and alarm mechanisms | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k         | 50M+         |
| Loki          | Log aggregation        | A lightweight log aggregation system developed by Grafana, similar to Prometheus but for logs | [grafana/loki](https://github.com/grafana/loki)              | 20.5k        | 200M+        |
| Vector        | Data Pipeline          | A high-performance observability data pipeline that supports collecting, transforming, and routing log data | [vectordotdev/vector](https://github.com/vectordotdev/vector) | 15.3k        | 20M+         |
| Graylog       | Log Platform           | Centralized log management platform, providing powerful search and alarm functions | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k         | 50M+         |
| Filebeat      | Log Collection         | A lightweight log file collector, part of the Elastic Beat family | [elastic/beats](https://github.com/elastic/beats)            | 11.8k        | 300M+        |
| SigNoz        | Observability Platform | An open source application performance monitoring and observability platform, an open source alternative to Datadog | [SigNoz/signoz](https://github.com/SigNoz/signoz)            | 15.2k        | 5M+          |
| GoAccess      | Log analysis           | Real-time web log analyzer and interactive viewer, supporting terminal and browser interfaces | [allinurl/goaccess](https://github.com/allinurl/goaccess)    | 16.4k        | 10M+         |

#### 🔍 Interface testing

| name       | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Postman    | Interface testing   | Powerful API development and testing tools that support automated testing and team collaboration | [postmanlabs/newman](https://github.com/postmanlabs/newman)  | 7.5k         | 50M+         |
| SoapUI     | Interface testing   | Professional API testing tool, supporting SOAP and REST interface testing | [SmartBear/soapui](https://github.com/SmartBear/soapui)      | 2.8k         | 5M+          |
| JMeter     | Performance Testing | Powerful load testing and performance testing tool, supporting multiple protocols | [apache/jmeter](https://github.com/apache/jmeter)            | 7.2k         | 100M+        |
| Gatling    | Performance Testing | A high-performance load testing tool developed based on Scala and supporting HTTP protocol | [gatling/gatling](https://github.com/gatling/gatling)        | 6.1k         | 20M+         |
| Locust     | Performance Testing | Distributed user load testing tool, using Python to write test scripts | [locustio/locust](https://github.com/locustio/locust)        | 22.8k        | 30M+         |
| Hoppscotch | API Platform        | A lightweight open source API development ecosystem that supports REST, GraphQL, and WebSocket | [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch) | 55.2k        | 10M+         |
| Karate     | Automated testing   | An open source tool that combines API testing, mocking, and performance testing | [karatelabs/karate](https://github.com/karatelabs/karate)    | 7.3k         | 5M+          |
| Insomnia   | API Client          | Cross-platform REST and GraphQL client, supporting environment variables and request management | [Kong/insomnia](https://github.com/Kong/insomnia)            | 30.5k        | 15M+         |
| Taurus     | Testing Framework   | Automated testing framework that can integrate tools such as JMeter and Gatling | [Blazemeter/taurus](https://github.com/Blazemeter/taurus)    | 1.8k         | 2M+          |

### 🔒 Cybersecurity

#### 🛡️ Firewall WAF

| name        | type                 | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| ModSecurity | WAF                  | Open source Web application firewall that provides real-time monitoring and protection functions | [SpiderLabs/ModSecurity](https://github.com/SpiderLabs/ModSecurity) | 6.2k         | 50M+         |
| NGINX WAF   | WAF                  | NGINX-based Web application firewall, providing high-performance HTTP filtering | [nginx/nginx](https://github.com/nginx/nginx)                | 19.5k        | 1B+          |
| OpenWAF     | WAF                  | Web application firewall based on OpenResty, supporting complex rules and high performance | [titansec/OpenWAF](https://github.com/titansec/OpenWAF)      | 1.2k         | 5M+          |
| Naxos       | WAF                  | NGINX's anti-XSS and SQL injection module is lightweight and efficient | [nbs-system/naxsi](https://github.com/nbs-system/naxsi)      | 4.8k         | 10M+         |
| Crowdsec    | Security Engine      | Open source security engine that detects and responds to malicious activity | [Crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) | 7.5k         | 15M+         |
| Wazuh       | Secure Platform      | Open source security monitoring platform, providing intrusion detection and security analysis | [wazuh/wazuh](https://github.com/wazuh/wazuh)                | 8.2k         | 100M+        |
| pfSense     | Firewall             | FreeBSD-based open source firewall and router platform       | [pfsense/pfsense](https://github.com/pfsense/pfsense)        | 4.5k         | 50M+         |
| OPNsense    | Firewall             | Open source firewall and routing platform based on HardenedBSD | [opnsense/core](https://github.com/opnsense/core)            | 3.2k         | 20M+         |
| Fail2Ban    | Intrusion Prevention | Scan log files and ban IPs that show signs of malicious activity | [fail2ban/fail2ban](https://github.com/fail2ban/fail2ban)    | 9.1k         | 100M+        |

#### 🔒 Security Audit

| name      | type                   | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| OpenVAS   | Vulnerability Scanning | Comprehensive vulnerability scanning and management solution, supporting multiple scanning methods | [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) | 3.8k         | 50M+         |
| OWASP ZAP | Security Testing       | The world's most popular free security testing tool for finding vulnerabilities in web applications | [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy)        | 11.5k        | 100M+        |
| Lynis     | Security Audit         | System security audit tool for evaluating the security status of Linux/Unix systems | [CISOfy/lynis](https://github.com/CISOfy/lynis)              | 11.2k        | 20M+         |
| OpenSCAP  | Compliance Check       | Open source security compliance solution that supports multiple security standards | [OpenSCAP/openscap](https://github.com/OpenSCAP/openscap)    | 1.5k         | 10M+         |
| Falco     | Runtime security       | Cloud native runtime security project, providing container, host and cloud security monitoring | [falcosecurity/falco](https://github.com/falcosecurity/falco) | 6.2k         | 100M+        |
| Osquery   | Security Analysis      | An operating system detection framework that uses the operating system as a high-performance relational database | [osquery/osquery](https://github.com/osquery/osquery)        | 20.5k        | 50M+         |
| Clair     | Container Scanning     | An open source project for static analysis of container vulnerabilities | [quay/clair](https://github.com/quay/clair)                  | 9.5k         | 100M+        |
| Trivy     | Vulnerability Scanning | Simple yet comprehensive container vulnerability scanner     | [aquasecurity/trivy](https://github.com/aquasecurity/trivy)  | 18.2k        | 500M+        |
| Anchore   | Container Analysis     | Deep container image analysis and policy engine              | [anchore/anchore-engine](https://github.com/anchore/anchore-engine) | 4.2k         | 50M+         |

#### 📈 Traffic Analysis

| name         | type                  | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------ | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Wireshark    | Traffic monitoring    | The world's most widely used network protocol analysis tool, providing deep packet inspection capabilities | [wireshark/wireshark](https://github.com/wireshark/wireshark) | 9.8k         | 50M+         |
| Ntopng       | Traffic monitoring    | High-performance network traffic monitoring and analysis tool, supporting real-time monitoring and historical data analysis | [ntop/ntopng](https://github.com/ntop/ntopng)                | 5.2k         | 20M+         |
| Zeek         | Protocol Analysis     | Powerful network security monitoring tool focusing on network traffic analysis and anomaly detection | [zeek/zeek](https://github.com/zeek/zeek)                    | 5.8k         | 10M+         |
| Suricata     | Intrusion Detection   | High-performance network threat detection engine, supporting IDS, IPS and NSM functions | [OISF/suricata](https://github.com/OISF/suricata)            | 7.2k         | 30M+         |
| Moloch       | Packet Capture        | Large-scale full-packet capture and indexing system for large-scale network monitoring | [arkime/arkime](https://github.com/arkime/arkime)            | 5.5k         | 5M+          |
| NetworkMiner | Forensic Analysis     | Network forensic analysis tool focused on extracting files and information from data packets | [netresec/networkminer](https://github.com/netresec/networkminer) | 2.1k         | 1M+          |
| Snort        | Intrusion Prevention  | Widely used open source intrusion detection and prevention system | [snort3/snort3](https://github.com/snort3/snort3)            | 3.8k         | 15M+         |
| Tshark       | Command line analysis | A command-line version of Wireshark, suitable for automated analysis and script integration | [wireshark/wireshark](https://github.com/wireshark/wireshark) | 9.8k         | 10M+         |

#### 🔍 Vulnerability Scanning

| name       | type                     | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Nmap       | Port Scanning            | The most popular network detection and security scanning tool | [nmap/nmap](https://github.com/nmap/nmap)                    | 8.5k         | 100M+        |
| Nuclei     | Web Scanning             | Fast and customizable vulnerability scanner                  | [ProjectDiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | 15.2k        | 50M+         |
| Nikto      | Web Scanning             | Web server scanner to detect dangerous files and outdated software | [sullo/nikto](https://github.com/sullo/nikto)                | 7.2k         | 20M+         |
| Masscan    | Port Scanning            | Internet-scale port scanner, blazingly fast                  | [robertdavidgraham/masscan](https://github.com/robertdavidgraham/masscan) | 21.5k        | 10M+         |
| Hydra      | Weak password detection  | Login password cracking tool, supports multiple protocols    | [vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) | 12.8k        | 30M+         |
| Acunetix   | Web Scanning             | Automated Web Application Security Testing Tools             | [acunetix/acunetix](https://www.acunetix.com/)               | -            | 5M+          |
| DefectDojo | Vulnerability Management | Security vulnerability management and collaboration platform | [DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | 3.2k         | 10M+         |
| X-ray      | Web Scanning             | Security assessment tool, supporting vulnerability scanning and crawling | [chaitin/xray](https://github.com/chaitin/xray)              | 8.9k         | 15M+         |
| Arachni    | Web Scanning             | Feature-rich web application security scanning framework     | [Arachni/arachni](https://github.com/Arachni/arachni)        | 4.2k         | 8M+          |
| OpenVAS    | Network Scanning         | Full-featured vulnerability scanner, supporting multiple vulnerability detection | [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) | 3.8k         | 50M+         |

#### 🍯 Honeypot system

| name       | type                     | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| T-Pot      | Comprehensive honeypot   | Multi-honeypot platform, integrating multiple honeypot systems and analysis tools | [telekom-security/tpotce](https://github.com/telekom-security/tpotce) | 4.8k         | 10M+         |
| HoneyDrive | Honeypot Collection      | Linux distribution with a variety of honeypots and analysis tools | [bruteforce-lab/honeydrive](https://github.com/bruteforce-lab/honeydrive) | 1.2k         | 1M+          |
| Cowrie     | SSH Honeypot             | Moderately interactive SSH and Telnet honeypot that records attacker behavior | [cowrie/cowrie](https://github.com/cowrie/cowrie)            | 4.5k         | 5M+          |
| Dionaea    | Multi-protocol honeypot  | Low-interaction honeypot for catching malware, supports multiple protocols | [DinoTools/dionaea](https://github.com/DinoTools/dionaea)    | 1.8k         | 2M+          |
| Glastopf   | Web Honeypot             | Low-interaction honeypot that simulates web application vulnerabilities | [mushorg/glastopf](https://github.com/mushorg/glastopf)      | 1.3k         | 1M+          |
| KFSensor   | Intrusion Detection      | Advanced Windows honeypot system, simulating various services | [kfsensor/kfsensor](https://github.com/kfsensor/kfsensor)    | 1k           | 500K+        |
| HoneyTrap  | Multifunctional honeypot | Extensible honeypot framework, supporting multiple protocols and services | [honeytrap/honeytrap](https://github.com/honeytrap/honeytrap) | 1.7k         | 1M+          |
| MHN        | Honeypot management      | Modern honeynet management system to simplify honeypot deployment and management | [threatstream/mhn](https://github.com/threatstream/mhn)      | 3.8k         | 2M+          |
| HonSSH     | SSH Agent                | SSH proxy honeypot, recording all SSH sessions of the attacker | [tnich/honssh](https://github.com/tnich/honssh)              | 1.1k         | 500K+        |

### 📊 Data Analysis

#### 📊 BI Tools

| name            | type                    | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------------- | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Metabase        | Data analysis           | Simple and powerful data analysis and visualization tools, supporting multiple data sources | [metabase/metabase](https://github.com/metabase/metabase)    | 35.2k        | 500M+        |
| Superset        | Data Exploration        | Apache open source modern data exploration and visualization platform | [apache/superset](https://github.com/apache/superset)        | 55.8k        | 200M+        |
| Redash          | Data Visualization      | Query and visualization tools that support multiple data sources, suitable for team collaboration | [getredash/redash](https://github.com/getredash/redash)      | 24.5k        | 100M+        |
| Grafana         | Monitoring and analysis | A powerful observability platform that supports multiple data sources and plugins | [grafana/grafana](https://github.com/grafana/grafana)        | 59.3k        | 3.2B+        |
| Cube.js         | Analytics Platform      | Open source analysis API platform to simplify complex data analysis | [cube-js/cube.js](https://github.com/cube-js/cube.js)        | 15.8k        | 50M+         |
| Apache Zeppelin | Data analysis           | Web-based data analysis and visualization notebooks          | [apache/zeppelin](https://github.com/apache/zeppelin)        | 6.2k         | 20M+         |
| Tableau         | Business Intelligence   | Professional data visualization and business intelligence tools | [tableau/tableau-server](https://github.com/tableau/tableau-server) | 2.5k         | 100M+        |
| Looker          | Data Platform           | Modern data platform, supporting custom data models          | [looker/looker](https://github.com/looker/looker)            | 1.8k         | 50M+         |
| PowerBI         | Business Analytics      | Microsoft's business analysis tool supports rich visualization effects | [microsoft/powerbi-docker](https://github.com/microsoft/powerbi-docker) | 1.5k         | 20M+         |

#### 📈 Data Visualization

| name       | type                       | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| ECharts    | Chart Library              | Baidu's open source powerful chart library supports a variety of visualization types | [apache/echarts](https://github.com/apache/echarts)          | 56.8k        | 100M+        |
| D3.js      | Visualization Library      | A flexible JavaScript data visualization library that supports custom charts | [d3/d3](https://github.com/d3/d3)                            | 106k         | 50M+         |
| Chart.js   | Chart Library              | Simple and easy-to-use JavaScript chart library, suitable for quick implementation | [chartjs/Chart.js](https://github.com/chartjs/Chart.js)      | 62.5k        | 200M+        |
| DataV      | Large screen visualization | Alibaba's open source data big screen solution supports a variety of visualization components | [DataV-Team/DataV](https://github.com/DataV-Team/DataV)      | 8.2k         | 10M+         |
| Plotly     | Interaction Analysis       | An interactive scientific visualization library supporting multiple programming languages | [plotly/plotly.js](https://github.com/plotly/plotly.js)      | 15.8k        | 80M+         |
| Highcharts | Business chart             | Powerful JavaScript chart library, supporting multiple chart types | [highcharts/highcharts](https://github.com/highcharts/highcharts) | 11.2k        | 150M+        |
| AntV       | Visualization Kit          | Ant Group's open source data visualization solution          | [antvis/G2](https://github.com/antvis/G2)                    | 11.5k        | 30M+         |
| Three.js   | 3D Visualization           | Popular JavaScript 3D visualization libraries                | [mrdoob/three.js](https://github.com/mrdoob/three.js)        | 94.8k        | 40M+         |
| Vega       | Declarative visualization  | Declarative visualization syntax supports complex interaction design | [vega/vega](https://github.com/vega/vega)                    | 10.2k        | 15M+         |

#### 🔄 Logging Engine

| name          | type                   | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Elasticsearch | Search Engines         | Distributed search and analysis engine, providing powerful full-text retrieval and data analysis capabilities | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k          | 1B+          |
| Logstash      | Data processing        | Dynamic data collection pipeline, supporting data collection and transformation from multiple sources | [elastic/logstash](https://github.com/elastic/logstash)      | 13.5k        | 500M+        |
| Kibana        | Visualization Platform | Data visualization and management interface make data analysis simple and intuitive | [elastic/kibana](https://github.com/elastic/kibana)          | 18.7k        | 500M+        |
| Fluentd       | Log Collection         | Unified log layer, supporting efficient log collection from multiple data sources | [fluent/fluentd](https://github.com/fluent/fluentd)          | 12.3k        | 100M+        |
| Loki          | Log aggregation        | Efficient log aggregation system, focusing on log storage and query | [grafana/loki](https://github.com/grafana/loki)              | 20.5k        | 200M+        |
| Vector        | Data Pipeline          | High-performance data pipeline tool for collecting, transforming, and routing observability data | [vectordotdev/vector](https://github.com/vectordotdev/vector) | 15.3k        | 20M+         |
| Graylog       | Log Platform           | Centralized log management platform, providing powerful search and alarm functions | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k         | 50M+         |
| Filebeat      | Log Collection         | A lightweight log file collector, part of the Elastic Beat family | [elastic/beats](https://github.com/elastic/beats)            | 11.8k        | 300M+        |
| SigNoz        | Observability Platform | An open source application performance monitoring and observability platform, an open source alternative to Datadog | [SigNoz/signoz](https://github.com/SigNoz/signoz)            | 15.2k        | 5M+          |
| GoAccess      | Log analysis           | Real-time web log analyzer and interactive viewer, supporting terminal and browser interfaces | [allinurl/goaccess](https://github.com/allinurl/goaccess)    | 16.4k        | 10M+         |

### 📝 Document Collaboration

#### 📄 Online Documentation

| name       | type                    | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Collabora  | Online Office Suite     | An online collaborative office suite based on LibreOffice that supports real-time editing of documents, spreadsheets, and presentations | [collabora/code](https://github.com/CollaboraOnline/online)  | 3.2k         | 10M+         |
| OnlyOffice | Online Office Suite     | A full-featured open source office suite that supports collaborative editing and version control of documents, spreadsheets, and presentations | [onlyoffice/documentserver](https://github.com/ONLYOFFICE/DocumentServer) | 4.5k         | 100M+        |
| Etherpad   | Live Documentation      | Highly customizable open source collaborative text editor that supports real-time editing and plugin extensions | [etherpad/etherpad-lite](https://github.com/ether/etherpad-lite) | 14.2k        | 10M+         |
| HedgeDoc   | Markdown Collaboration  | Real-time collaborative Markdown editor, supporting multiple formats export and permission management | [hedgedoc/hedgedoc](https://github.com/hedgedoc/hedgedoc)    | 4.8k         | 5M+          |
| Cryptpad   | Encrypted collaboration | Zero-knowledge encrypted collaboration platform that supports secure collaboration of multiple file types including documents, spreadsheets, presentations, etc. | [cryptpad/cryptpad](https://github.com/cryptpad/cryptpad)    | 5.2k         | 2M+          |

#### 📚 Knowledge Management

| name       | type                   | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Wikijs     | knowledge base         | A modern open source Wiki system that supports Markdown editing, permission management and multiple languages | [requarks/wiki](https://github.com/requarks/wiki)            | 21.5k        | 50M+         |
| BookStack  | Document Management    | A simple and elegant document management system that supports chapter organization and version control | [bookstackapp/bookstack](https://github.com/BookStackApp/BookStack) | 12.8k        | 30M+         |
| Outline    | knowledge base         | Team knowledge base and document management tool, supporting Markdown and real-time collaboration | [outline/outline](https://github.com/outline/outline)        | 20.1k        | 10M+         |
| Documize   | Document collaboration | Intelligent document collaboration platform, supporting template and workflow integration | [documize/community](https://github.com/documize/community)  | 1.8k         | 1M+          |
| Docusaurus | Documentation website  | Easy-to-maintain open source documentation website generator with version control and multi-language support | [facebook/docusaurus](https://github.com/facebook/docusaurus) | 49.2k        | 5M+          |

#### 📋 Project Management

| name        | type               | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Wekan       | Kanban Tools       | An open source board tool similar to Trello that supports drag-and-drop operations and team collaboration | [wekan/wekan](https://github.com/wekan/wekan)                | 18.7k        | 20M+         |
| Taiga       | project management | Agile project management platform supporting Scrum and Kanban methodologies | [taigaio/taiga](https://github.com/taigaio/taiga)            | 6.2k         | 5M+          |
| Planka      | Kanban Tools       | Open source project management tool that supports real-time collaboration and task tracking | [plankanban/planka](https://github.com/plankanban/planka)    | 5.1k         | 2M+          |
| Focalboard  | project management | Open source project management tool, alternative to Notion and Trello | [mattermost/focalboard](https://github.com/mattermost/focalboard) | 16.5k        | 5M+          |
| OpenProject | project management | Professional project management software supporting Gantt charts and agile methods | [opf/openproject](https://github.com/opf/openproject)        | 7.8k         | 10M+         |

#### ✏️ Note-taking tools

| name           | type             | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Joplin         | Note-taking apps | Open source note-taking and to-do app with Markdown support and end-to-end encryption | [joplin/server](https://github.com/laurent22/joplin)         | 38.5k        | 5M+          |
| Trilium        | knowledge base   | Hierarchical note application, supporting rich note formats and script extensions | [zadam/trilium](https://github.com/zadam/trilium)            | 22.3k        | 10M+         |
| Standard Notes | Encrypted Notes  | End-to-end encrypted note-taking app that focuses on privacy and long-term data preservation | [standardnotes/app](https://github.com/standardnotes/app)    | 4.2k         | 2M+          |
| AppFlowy       | Workspace        | An open source Notion alternative that supports database views and document collaboration | [appflowy/appflowy](https://github.com/AppFlowy-IO/AppFlowy) | 42.1k        | 1M+          |
| Logseq         | Knowledge Graph  | Privacy-first knowledge management and collaboration platform with outline and bidirectional linking support | [logseq/logseq](https://github.com/logseq/logseq)            | 26.8k        | 1M+          |

### ☁️ Cloud storage

#### 📁 File Storage

| name        | type            | Application Introduction                                     | Open source address                                     | GitHub Stars | Docker Pulls |
| ----------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------- | ------------ | ------------ |
| Nextcloud   | File Storage    | A comprehensive private cloud storage platform that supports file synchronization, sharing and collaboration | [nextcloud/server](https://github.com/nextcloud/server) | 24.5k        | 1B+          |
| Seafile     | File Storage    | High-performance file synchronization and sharing platform, focusing on security and reliability | [haiwen/seafile](https://github.com/haiwen/seafile)     | 11.2k        | 100M+        |
| Owncloud    | File Storage    | Open source personal cloud storage solution that provides file access and synchronization capabilities | [owncloud/core](https://github.com/owncloud/core)       | 8.5k         | 500M+        |
| FileRun     | File Management | A lightweight file management system that supports online preview and editing of files | [filerun/filerun](https://github.com/filerun/filerun)   | 2.1k         | 10M+         |
| Pydio Cells | File Platform   | Enterprise-class file sharing platform with advanced rights management and collaboration features | [pydio/cells](https://github.com/pydio/cells)           | 1.8k         | 5M+          |

#### 🗄️ Object Storage

| name   | type                | Application Introduction                                     | Open source address                                   | GitHub Stars | Docker Pulls |
| ------ | ------------------- | ------------------------------------------------------------ | ----------------------------------------------------- | ------------ | ------------ |
| MinIO  | Object Storage      | High-performance distributed object storage service, compatible with Amazon S3 API | [minio/minio](https://github.com/minio/minio)         | 41.2k        | 1B+          |
| Ceph   | Storage System      | Distributed storage system that provides object, block and file storage capabilities | [ceph/ceph](https://github.com/ceph/ceph)             | 12.5k        | 100M+        |
| Zenko  | Multi-cloud storage | Multi-cloud data controller, supporting cross-cloud storage management and migration | [scality/zenko](https://github.com/scality/zenko)     | 1.2k         | 10M+         |
| Swift  | Object Storage      | OpenStack's object storage project, a scalable distributed storage system | [openstack/swift](https://github.com/openstack/swift) | 2.5k         | 50M+         |
| Garage | Object Storage      | Lightweight S3-compatible object storage service, suitable for edge computing scenarios | [garagehq/garage](https://github.com/garagehq/garage) | 3.8k         | 5M+          |

#### 🔄 Synchronous backup

| name       | type         | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Syncthing  | File Sync    | A decentralized continuous file synchronization tool with a focus on privacy and security | [syncthing/syncthing](https://github.com/syncthing/syncthing) | 55.8k        | 100M+        |
| Duplicati  | Backup Tools | Encrypted online backup tool that supports multiple cloud storage services | [duplicati/duplicati](https://github.com/duplicati/duplicati) | 9.2k         | 50M+         |
| Restic     | Backup Tools | Fast, secure and efficient backup program, supporting multiple back-end storage | [restic/restic](https://github.com/restic/restic)            | 21.5k        | 20M+         |
| Kopia      | Backup Tools | Cross-platform backup tool that supports encryption, deduplication and compression | [kopia/kopia](https://github.com/kopia/kopia)                | 5.2k         | 10M+         |
| BorgBackup | Backup Tools | Deduplication backup program, compression and encryption support | [borgbackup/borg](https://github.com/borgbackup/borg)        | 9.8k         | 15M+         |

#### 💾Network disk system

| name        | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Cloudreve   | Network disk system | Supports multiple cloud storage systems, with online file preview and sharing functions | [cloudreve/cloudreve](https://github.com/cloudreve/cloudreve) | 18.5k        | 20M+         |
| Filebrowser | File Management     | Simple file management interface, supports file upload, deletion, preview and sharing | [filebrowser/filebrowser](https://github.com/filebrowser/filebrowser) | 22.3k        | 100M+        |
| AriaNg      | Download the tool   | Aria2's web frontend supports offline download and BT download functions | [mayswind/AriaNg](https://github.com/mayswind/AriaNg)        | 10.8k        | 50M+         |
| Filestash   | File Management     | Modern web file manager, supporting FTP, SFTP, WebDAV and other protocols | [mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash) | 8.2k         | 10M+         |
| Rclone      | Cloud Storage Tools | A command line tool for managing files on cloud storage, supporting multiple cloud storage services | [rclone/rclone](https://github.com/rclone/rclone)            | 40.5k        | 30M+         |

### 🎮 Game Servers

#### 🎲 Game Management

| name        | type              | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Pterodactyl | Game Panel        | Powerful game server management panel, supporting multiple games and automated deployment | [pterodactyl/panel](https://github.com/pterodactyl/panel)    | 12.5k        | 50M+         |
| LinuxGSM    | Server Management | Linux game server manager, supports installation and management of various game servers | [GameServerManagers/LinuxGSM](https://github.com/GameServerManagers/LinuxGSM) | 4.8k         | 10M+         |
| Cuberite    | MC Server         | A high-performance Minecraft server written in C++ with a focus on performance and scalability | [cuberite/cuberite](https://github.com/cuberite/cuberite)    | 3.9k         | 5M+          |
| Velocity    | MC Agent          | Modern Minecraft proxy server, supporting multi-server cluster and load balancing | [PaperMC/Velocity](https://github.com/PaperMC/Velocity)      | 2.1k         | 15M+         |
| SteamCMD    | Steam Tools       | Steam game server command line tool for installing and updating game servers | [steamcmd/steamcmd](https://github.com/steamcmd/steamcmd)    | 1.5k         | 100M+        |
| Crafty      | MC Manager        | Simple and easy to use Minecraft server web management panel | [CraftyControl/Crafty](https://github.com/CraftyControl/Crafty) | 1.2k         | 2M+          |

#### 🛠️ Gaming Tools

| name     | type               | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------- | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| MCRcon   | Remote Control     | RCON client for Minecraft servers, supports remote command execution | [Tiiffi/mcrcon](https://github.com/Tiiffi/mcrcon)            | 1.8k         | 5M+          |
| AMP      | Service Monitoring | Game server application management panel, supporting performance monitoring and automatic restart | [CubeCoders/AMP](https://github.com/CubeCoders/AMP)          | 1.2k         | 3M+          |
| ARRCON   | Remote Management  | Universal game server RCON tool, supporting multiple game protocols | [radj307/ARRCON](https://github.com/radj307/ARRCON)          | 0.8k         | 1M+          |
| GameDig  | Status Query       | Game server status query library, supporting multiple game protocols | [gamedig/node-gamedig](https://github.com/gamedig/node-gamedig) | 2.1k         | 2M+          |
| LGSM-Web | Web Panel          | LinuxGSM's Web management interface provides graphical server management | [GameServerManagers/LGSM-Web](https://github.com/GameServerManagers/LGSM-Web) | 0.5k         | 1M+          |

#### 🎯 Minecraft Servers

| name      | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Paper     | MC Server           | High performance Minecraft server, based on an optimized fork of Spigot | [PaperMC/Paper](https://github.com/PaperMC/Paper)            | 8.2k         | 80M+         |
| Spigot    | MC Server           | Popular Minecraft server with plugin support and high customization | [SpigotMC/Spigot](https://github.com/SpigotMC/Spigot)        | 4.5k         | 60M+         |
| Purpur    | MC Server           | A high-performance server based on Paper with more customization options | [PurpurMC/Purpur](https://github.com/PurpurMC/Purpur)        | 1.8k         | 20M+         |
| Waterfall | MC Agent            | High-performance Minecraft proxy server, optimized branch of BungeeCord | [PaperMC/Waterfall](https://github.com/PaperMC/Waterfall)    | 1.5k         | 15M+         |
| MineOS    | MC Management Panel | Web-based Minecraft server control panel                     | [hexparrot/mineos-node](https://github.com/hexparrot/mineos-node) | 1.2k         | 5M+          |
| McMyAdmin | MC Management Panel | Professional Minecraft server management panel, supporting plugin and module management | [McMyAdmin/MCMA](https://github.com/McMyAdmin/MCMA)          | 0.9k         | 10M+         |

#### 🎲 Multiplayer Servers

| name     | type               | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------- | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Valheim  | Norse mythology    | Valheim dedicated server, supporting mods and world saves    | [lloesche/valheim-server](https://github.com/lloesche/valheim-server) | 2.8k         | 30M+         |
| Factorio | Factory simulation | Factorio dedicated server, supports multiplayer and MOD      | [factoriotools/factorio](https://github.com/factoriotools/factorio) | 1.5k         | 25M+         |
| Terraria | Sandbox Adventure  | Terraria dedicated server, supports multiplayer and map management | [beardedio/terraria](https://github.com/beardedio/terraria)  | 1.2k         | 20M+         |
| CS:GO    | Shooting Games     | Counter-Strike: Global Offensive dedicated servers           | [CM2Walki/csgo](https://github.com/CM2Walki/csgo)            | 1.1k         | 40M+         |
| ARK      | Survival Game      | ARK: Survival Evolved dedicated server, supporting mods and multiple maps | [thmhoag/arkserver](https://github.com/thmhoag/arkserver)    | 0.9k         | 15M+         |
| Rust     | Survival Game      | Rust-specific server with plugin support and custom configuration | [Didstopia/rust-server](https://github.com/Didstopia/rust-server) | 0.8k         | 35M+         |

### 📡 Web Tools

#### 🌐 Web Proxy

| name                | type                 | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Traefik             | Reverse Proxy        | Modern HTTP reverse proxy and load balancer with automatic service discovery and SSL configuration | [traefik/traefik](https://github.com/traefik/traefik)        | 45k          | 10B+         |
| HAProxy             | Load Balancing       | High-performance TCP/HTTP load balancer, supporting multiple load balancing algorithms | [haproxy/haproxy](https://github.com/haproxy/haproxy)        | 4.2k         | 1B+          |
| Nginx Proxy Manager | Reverse Proxy        | Visual Nginx configuration tool, supporting automated management of SSL certificates | [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager) | 16k          | 100M+        |
| Squid               | Forward Proxy        | Feature-rich web caching proxy server with support for access control and cache management | [squid-cache/squid](https://github.com/squid-cache/squid)    | 1.5k         | 500M+        |
| Caddy               | Reverse Proxy        | Automatic HTTPS web server, simple configuration, excellent performance | [caddyserver/caddy](https://github.com/caddyserver/caddy)    | 50k          | 200M+        |
| 3proxy              | Multi-protocol proxy | A lightweight proxy server that supports multiple proxy protocols such as HTTP, SOCKS, FTP, etc. | [3proxy/3proxy](https://github.com/3proxy/3proxy)            | 2.8k         | 50M+         |
| Envoy               | Service Agent        | Cloud-native high-performance edge and service proxy, supporting service mesh | [envoyproxy/envoy](https://github.com/envoyproxy/envoy)      | 22k          | 500M+        |
| NGINX               | Reverse Proxy        | High-performance HTTP and reverse proxy servers, supporting load balancing and caching | [nginx/nginx](https://github.com/nginx/nginx)                | 18k          | 10B+         |

#### 🔐 VPN Service

| name        | type           | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| OpenVPN     | VPN Services   | The most popular open source VPN solution, supporting multiple authentication methods and encryption protocols | [OpenVPN/openvpn](https://github.com/OpenVPN/openvpn)        | 8.2k         | 500M+        |
| WireGuard   | VPN Services   | A new generation of high-performance VPN protocol implementation, simple configuration, excellent performance | [WireGuard/wireguard-tools](https://github.com/WireGuard/wireguard-tools) | 7.1k         | 200M+        |
| Pritunl     | VPN Management | Enterprise-level OpenVPN server management platform, supporting multi-server deployment | [pritunl/pritunl](https://github.com/pritunl/pritunl)        | 5.2k         | 50M+         |
| OpenConnect | VPN Services   | Cisco AnyConnect-compatible open source VPN client and server | [openconnect/openconnect](https://github.com/openconnect/openconnect) | 3.1k         | 30M+         |
| SoftEther   | VPN Services   | Multi-protocol VPN server, supporting SSL-VPN, L2TP and IPsec | [SoftEtherVPN/SoftEtherVPN](https://github.com/SoftEtherVPN/SoftEtherVPN) | 9.8k         | 100M+        |

#### 🌍 DNS service

| name           | type           | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Pi-hole        | Ad filtering   | A black hole for network-level ads and internet trackers, providing DNS-level ad blocking | [pi-hole/pi-hole](https://github.com/pi-hole/pi-hole)        | 42k          | 1B+          |
| CoreDNS        | DNS Server     | Flexible and scalable DNS server, supporting multiple backend storage and plug-in systems | [coredns/coredns](https://github.com/coredns/coredns)        | 10.5k        | 10B+         |
| AdGuard Home   | Ad filtering   | Network-wide ad and tracker blocking DNS servers             | [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) | 18k          | 500M+        |
| Technitium DNS | DNS Management | Cross-platform open source DNS server, supporting DNS-over-HTTPS and DNS-over-TLS | [TechnitiumSoftware/DnsServer](https://github.com/TechnitiumSoftware/DnsServer) | 2.5k         | 50M+         |
| PowerDNS       | DNS Server     | Enterprise-level DNS server, supporting multiple backend databases and high-availability configurations | [PowerDNS/pdns](https://github.com/PowerDNS/pdns)            | 3k           | 100M+        |
| Unbound        | DNS Resolver   | Validating, recursive, and caching DNS resolver with a focus on security and performance | [NLnetLabs/unbound](https://github.com/NLnetLabs/unbound)    | 1.2k         | 200M+        |
| BIND           | DNS Server     | The most widely used DNS software, providing complete DNS server functionality | [isc-projects/bind9](https://github.com/isc-projects/bind9)  | 2.8k         | 300M+        |
| DNSCrypt-proxy | DNS Encryption | DNS proxy that supports modern encrypted DNS protocols, improving the security and privacy of DNS queries | [DNSCrypt/dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) | 10k          | 100M+        |

#### 📡 Network Monitoring

| name       | type                 | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ---------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Prometheus | Monitoring system    | Open source monitoring and alarm system, supporting multi-dimensional data models and powerful query language | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k        | 2B+          |
| Zabbix     | Monitoring Platform  | Enterprise-level distributed monitoring solution, supporting automatic discovery and template management | [zabbix/zabbix](https://github.com/zabbix/zabbix)            | 4.2k         | 500M+        |
| Grafana    | Visualization        | Powerful indicator data and log visualization platform, supporting multiple data sources | [grafana/grafana](https://github.com/grafana/grafana)        | 58k          | 3B+          |
| Nagios     | Monitoring system    | Classic IT infrastructure monitoring system, supporting plug-in extensions and custom monitoring | [NagiosEnterprises/nagioscore](https://github.com/NagiosEnterprises/nagioscore) | 2.8k         | 50M+         |
| Netdata    | Real-time monitoring | Distributed real-time performance and health monitoring system with low resource usage | [netdata/netdata](https://github.com/netdata/netdata)        | 65.2k        | 1B+          |

### 🤝 Collaborative Office

#### 💬 Team communication

| name        | type              | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Rocket.Chat | Instant Messaging | Feature-rich team chat platform that supports real-time messaging, file sharing, and video conferencing | [RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) | 37.2k        | 500M+        |
| Mattermost  | Teamwork          | An open source enterprise-level team communication platform that supports messaging, file sharing, and integration | [mattermost/mattermost](https://github.com/mattermost/mattermost) | 27.1k        | 100M+        |
| Element     | Instant Messaging | Secure communication tool based on Matrix protocol, supporting end-to-end encryption | [vector-im/element-web](https://github.com/vector-im/element-web) | 9.2k         | 50M+         |
| Jitsi Meet  | videoconference   | High-quality open source video conferencing platform with support for screen sharing and chat | [jitsi/jitsi-meet](https://github.com/jitsi/jitsi-meet)      | 20.3k        | 200M+        |
| Let's Chat  | Team Chat         | Lightweight team chat app with file upload and emoticon support | [sdelements/lets-chat](https://github.com/sdelements/lets-chat) | 9.5k         | 10M+         |

#### 👥 Project Collaboration

| name        | type                      | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ----------- | ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Redmine     | project management        | Flexible project management and issue tracking system, supporting multiple projects and time tracking | [redmine/redmine](https://github.com/redmine/redmine)        | 4.8k         | 100M+        |
| Kanboard    | Kanban Tools              | Simple and powerful visual project management tool that supports task management and time tracking | [kanboard/kanboard](https://github.com/kanboard/kanboard)    | 7.8k         | 50M+         |
| Leantime    | project management        | Lean project management system for small teams and startups  | [leantime/leantime](https://github.com/leantime/leantime)    | 3.2k         | 5M+          |
| Phabricator | Development Collaboration | A complete software development collaboration platform that supports code review and task management | [phacility/phabricator](https://github.com/phacility/phabricator) | 12.1k        | 20M+         |
| Tuleap      | project management        | Enterprise-level open source project management platform that supports agile development and document management | [Enalean/tuleap](https://github.com/Enalean/tuleap)          | 1.2k         | 5M+          |

#### ⚡ Workflow

| name         | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------ | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| n8           | Workflow Automation | Powerful workflow automation tool that supports multiple service integrations and custom nodes | [n8n-io/n8n](https://github.com/n8n-io/n8n)                  | 39.1k        | 63M+         |
| Camunda      | Process Engine      | An open source business process management platform that supports BPMN workflow modeling and execution | [camunda/camunda-bpm](https://github.com/camunda/camunda-bpm) | 4.2k         | 28M+         |
| Formio       | Form Platform       | Enterprise-level form and API platform, supporting drag-and-drop form design and workflow | [formio/formio](https://github.com/formio/formio)            | 2.9k         | 10M+         |
| ProcessMaker | Workflow Platform   | Enterprise-level business process management system, supporting process design and form management | [processmaker/processmaker](https://github.com/processmaker/processmaker) | 2.1k         | 5M+          |
| Activiti     | Workflow Engine     | Lightweight business process engine, supporting BPMN 2.0 standard | [Activiti/Activiti](https://github.com/Activiti/Activiti)    | 9.5k         | 15M+         |

#### 📊 Resource Management

| name      | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| --------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| ERPNext   | ERP System          | Comprehensive enterprise resource planning system supporting financial, inventory and human resource management | [frappe/erpnext](https://github.com/frappe/erpnext)          | 15.8k        | 50M+         |
| Odoo      | Business Management | Modular enterprise management software covering CRM, finance, inventory and other fields | [odoo/odoo](https://github.com/odoo/odoo)                    | 31.2k        | 100M+        |
| Snipe-IT  | asset Management    | IT asset management system to support equipment tracking and maintenance management | [snipe/snipe-it](https://github.com/snipe/snipe-it)          | 8.9k         | 20M+         |
| Dolibarr  | Business Management | ERP/CRM system for small and medium-sized enterprises, supporting sales, finance and inventory management | [Dolibarr/dolibarr](https://github.com/Dolibarr/dolibarr)    | 4.2k         | 10M+         |
| OrangeHRM | human Resources     | Comprehensive human resources management system, supporting employee information and attendance management | [orangehrm/orangehrm](https://github.com/orangehrm/orangehrm) | 1.8k         | 5M+          |

### 🗂️ Personal knowledge management

#### 📝 Note system

| name     | type             | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Joplin   | Note-taking apps | Open source note-taking and to-do app with Markdown support and end-to-end encryption | [joplin/server](https://github.com/laurent22/joplin)         | 38.5k        | 5M+          |
| Trilium  | knowledge base   | Hierarchical note application, supporting rich note formats and script extensions | [zadam/trilium](https://github.com/zadam/trilium)            | 22.3k        | 10M+         |
| AppFlowy | Workspace        | An open source Notion alternative that supports database views and document collaboration | [appflowy/appflowy](https://github.com/AppFlowy-IO/AppFlowy) | 42.1k        | 1M+          |
| Logseq   | Knowledge Graph  | Privacy-first knowledge management and collaboration platform with outline and bidirectional linking support | [logseq/logseq](https://github.com/logseq/logseq)            | 26.8k        | 1M+          |
| Dendron  | knowledge base   | A hierarchical note system based on VSCode, suitable for developers | [dendronhq/dendron](https://github.com/dendronhq/dendron)    | 4.2k         | 500k+        |

#### ✅ Task management

| name               | type            | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------------ | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Vikunja            | Task Management | Modern to-do and project management tool with support for Kanban and list views | [vikunja/vikunja](https://github.com/go-vikunja/vikunja)     | 3.2k         | 2M+          |
| Super Productivity | Time Management | Personal productivity tool with integrated Pomodoro timer and task tracking | [johannesjo/super-productivity](https://github.com/johannesjo/super-productivity) | 8.1k         | 500k+        |
| Habitica           | Habit Formation | Task management tools that gamify habit formation            | [HabitRPG/habitica](https://github.com/HabitRPG/habitica)    | 10.2k        | 1M+          |
| TaskBoard          | Task Board      | Simple task management tool for individuals and small teams  | [kiswa/taskboard](https://github.com/kiswa/taskboard)        | 1.2k         | 200k+        |
| Tracks             | Time Management | Task management system based on GTD concept                  | [TracksApp/tracks](https://github.com/TracksApp/tracks)      | 1.5k         | 100k+        |

#### 🔖 Bookmark Management

| name     | type                        | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| -------- | --------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Linking  | Bookmark Management         | A simple personal bookmark management tool that supports tags and search functions | [sissbruecker/linkding](https://github.com/sissbruecker/linkding) | 3.8k         | 5M+          |
| Shiori   | Bookmark Management         | Simple self-hosted bookmark manager with support for offline reading and tags | [go-shiori/shiori](https://github.com/go-shiori/shiori)      | 8.5k         | 2M+          |
| Shaarli  | Link Sharing                | A personal link sharing platform that supports private and public sharing | [shaarli/shaarli](https://github.com/shaarli/shaarli)        | 4.2k         | 1M+          |
| Wallabag | Read later                  | A tool for saving web page content, supporting tags and full-text search | [wallabag/wallabag](https://github.com/wallabag/wallabag)    | 7.8k         | 10M+         |
| Pinry    | Picture and Text Collection | Image bookmarking tool, self-hosted solution similar to Pinterest | [pinry/pinry](https://github.com/pinry/pinry)                | 3.1k         | 500k+        |

#### 👤 Profile

| name          | type                | Application Introduction                                     | Open source address                                          | GitHub Stars | Docker Pulls |
| ------------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------------ |
| Bitwarden     | Password Management | Secure password manager with multi-device synchronization and password sharing | [bitwarden/server](https://github.com/bitwarden/server)      | 12.8k        | 50M+         |
| Monica        | Personal CRM        | Personal relationship management system, recording contact information and interactions | [monicahq/monica](https://github.com/monicahq/monica)        | 19.2k        | 10M+         |
| Paperless-ngx | Document Management | Document scanning and filing system with OCR and automatic labeling support | [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | 12.5k        | 5M+          |
| Wagtail       | Personal website    | Flexible personal website and blog system, developed based on Django | [Wagtail/wagtail](https://github.com/wagtail/wagtail)        | 15.8k        | 2M+          |
| RedNotebook   | Journaling Tools    | A personal diary app that supports tags and templates        | [jendrikseipp/rednotebook](https://github.com/jendrikseipp/rednotebook) | 2.1k         | 100k+        |

## Contribution Guidelines

Contributions are welcome! Please read [the contribution guide](https://github.com/arch3rPro/Awesome-Docker/blob/main/CONTRIBUTING.md) to learn how to get started.

### Contribution Standards

- Ensure suggested resources are of high quality
- Please provide a brief Chinese description when adding a new resource
- Keep your categories neat and logical
- Check link validity