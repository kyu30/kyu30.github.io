# Data Science Student

#### Technical Skills: Python, SQL, Rust, R

## Education
- B.S., Data Science, Business Minor @ Boston University (_September 2023 - June 2026_)
- M.S., Data Science & Analytics @ Georgetown University (_August 2026 - December 2027_)

## Work Experience
**Bank Tech Intern @ Capital One (_June 2026 - August 2026_)**
- Led migration of Python microservices from a Kubernetes-hosted business rule execution platform to modern destination environments, defining migration patterns across 5+ target runtime architectures.
- Engineered and wrote documentation for Claude skills to assist in and automate migration, cutting time spent on manual migration by 40%
- Developed expertise in big data processing principles and tooling, supporting applications built on Kafka-based event streaming and distributed parallel processing on Kubernetes clusters.

**Software Intern @ Cushman & Wakefield (_September 2025 - January 2026_)**
- Designed and deployed a PDF-to-CSV parsing app using Flask, Python, and the PDFplumber and regex libraries, cutting portfolio preparation time by 50% and enabling faster delivery of client presentations.
- Developed a Python script leveraging regex to transform a dataset of 2,000+ company contacts into a standardized reporting template, eliminating hours of manual formatting.
- Automated data collection using the SEC's EDGAR API to create PowerBI graphics for clients involving competitive analysis and portfolio overviews

**Technical Consultant @ SQO Marketing (_October 2024 - June 2025_)**
- Completed 3 web development projects centered around integrations for a Webflow website using Zapier and Make
- Automated the formatting and migration of over 50 client financial records to a Stripe database using JavaScript and Stripe API tools
- Provided technical insight for equipment purchases, cybersecurity, and web development decisions

**Co-Owner and Technology Lead @ The Collector's Bar (_April 2024 - Present_)**
- Constructed and developed a RFID door access system using a network of Arduino microcomputers through Docker-hosted Mosquitto server and integrated into building security system
- Developed a full-stack web app and database using Python, JavaScript, SQL, and HTML with Heroku to remotely monitor and automatically update company access card database
- Developing risk management algorithm to track and identify potential causes of financial losses

## Projects
### Fossil Fuel Native Ads
[Dashboard](https://huggingface.co/spaces/spark-ds549/Claims2)
- Built a UI for claims-based analysis of sponsored climate and energy articles, mapping each sentence/paragraph to subclaim–superclaim pairs with confidence scores.
- Applied BERTopic to cluster and collapse related claims, helping refine a hierarchical claim typology for the new CLAIMS 2.0. model
- Supported an interpretable research workflow for analyzing rhetorical strategies and misinformation themes in fossil-fuel native advertising.

### Drum Break Sound Gen
[Git Repo](https://github.com/kyu30/sound_gen)
- Designed and trained custom convolutional VAE and VQ-VAE models to learn 2-second drum break sample spectrograms to produce original sound
- Wrote scripts to reconstruct sound from model outputs and create spectrograms for data visualization
- Generated over 1,000 structured but noisy reconstructions and novel generative samples; analyzed model limitations and improved results with normalization and KL-annealing.

### Spotify Recommend
[Git Repo](https://github.com/kyu30/SpotifyRecSys)
- Built a recommendation system using a dataset of over 140,000 tracks containing audio statistics from Spotify’s WebAPI
- Used Rust modules to measure the centrality of each track and recommend to the user the 5 statistically closest tracks to a given track
- Applied algorithms and metrics such as K-Nearest Neighbors and closeness centrality, working with graph algorithms and structures
