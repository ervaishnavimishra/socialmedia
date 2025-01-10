# Overview
I built this tool to help analyze social media content performance using DataStax Astra DB and Langflow. It's a project for the Level Supermind Hackathon that looks at how different types of posts (photos, videos, reels,etc.) perform and gives you useful insights about what works best.

# What This Tool Does
- **Analyzes** how well your posts are doing in real-time  
- **Uses GPT** to give you content suggestions  
- **Helps** find similar content  
- **Predicts** how new content might perform  

# How It Works
### The Main Parts:
#### **DataStax Astra DB**
- Stores and organizes all your post data  
- Makes it easy to find similar content  
- Handles lots of data smoothly  

#### **Langflow**
- Connects everything together  
- Processes data automatically  
- Works with GPT to give you insights    

# Getting Started 🔧
## Prerequisites
- DataStax Astra DB account  
- OpenAI API key  
- Python 3.8+  
- Langflow  

## Installation
1. **Clone the repository**  
   ```bash
   git clone https://github.com/ervaishnavimishra/socialmedia.git
## Set Up Environment Variables

### Run the following command to create the `.env` file:
```bash
cp .env.example .env
```

### Edit with your credentials 
```bash
ASTRA_DB_APPLICATION_TOKEN=your_token
ASTRA_DB_API_ENDPOINT=your_endpoint
OPENAI_API_KEY=your_key
```
## Install Langflow
``` bash 
pip install langflow
```

### Run Langflow
```bash
langflow run
```
## Getting Started With The Project : 
This project is easy to replicate using the provided sample data:

### Get the Data
- Check the dataset.csv file for the sample dataset 
- Contains 25 social media posts with likes, comments, shares, etc.
- Real-world engagement patterns included
- Upload this data in your astra db
### Set Up the Flow
- Import the Langflow JSON file (assignment.json)
- This sets up the entire workflow automatically
### Configure DataStax
- Use your Astra DB credentials
- Collection name: social_media_analysis
- Import mock data using the provided script

## Acknowledgments 
- Level Supermind Hackathon
- DataStax Team
- Langflow Community
