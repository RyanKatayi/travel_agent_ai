# ✈️ AI-Powered Travel Assistant

Welcome to the AI-Powered Travel Assistant! This Streamlit app uses OpenAI GPT-4 to create personalized travel plans, making it easy to plan your dream vacation with detailed itineraries, destination insights, and activity suggestions.

## Key Features

- **Explore Destinations:** Discover unique travel spots, activities, and lodging options.
- **Custom Itineraries:** Adjust your travel plans based on the duration of your trip.
- **AI-Driven Planning:** Leverage GPT-4 to develop smart and bespoke travel itineraries.

## Setup Instructions

### Step 1: Clone the Repository

Begin by cloning the GitHub repository to your local machine:

```bash
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
```
### Step 2: Install Dependencies

Navigate to the project directory and install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Step 3: Obtain API Keys

#### OpenAI API Key

Register for an OpenAI account and generate your API key.

#### SerpAPI Key

Create an account on SerpAPI and obtain your API key.

### Step 4: Launch the Application

Run the Streamlit app with the following command:

```bash
streamlit run travel_agent.py
```

## How It Operates

The AI-Powered Travel Assistant is divided into two main modules:

- **Search Module:** Creates search queries based on your chosen destination and trip length, using SerpAPI to find relevant activities and accommodations.

- **Itinerary Module:** Uses the search results and your preferences to compile a customized itinerary with activity suggestions tailored to your interests and schedule.