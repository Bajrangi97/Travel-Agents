# Travel Planner Agents 

Travel Planner Agents are dedicated to crafting personalized and comprehensive travel itineraries tailored to your specific needs. By considering your travel origin, destination, interests, date range, and the number of travelers, our agents curate the perfect travel plan, ensuring an engaging and memorable experience.

This project demonstrates how autonomous AI agents can collaborate and execute complex tasks efficiently, with a user-friendly Streamlit interface.

## Project Structure
The project consists of the following files and directories:

`agents.py :`  Defines Crew AI agents responsible for specific tasks in the travel itinerary planning process, such as gathering user preferences, searching for relevant destinations and activities, and curating the final itinerary.

`tasks.py :`  Defines Crew AI tasks for each agent involved in the travel itinerary planning process, such as collecting user input, fetching travel data from various sources, and generating the itinerary.

`search_tools.py :`  Provides custom search tools using APIs (e.g., SERPER) to gather relevant information for travel planning, such as destinations, attractions, accommodations, and transportation options.

`file_io.py :`  Contains functions for saving the generated travel itinerary in markdown format.

`main.py :`  The main script that instantiates Crew AI agents, tasks, and the language model (e.g., LLaMA 3.1 (70b)). It then forms a Crew object and kicks off the travel itinerary planning process.

`app.py :` Defines and creates the Streamlit application, providing a user-friendly interface for users to input their travel preferences and receive personalized itineraries.

`.env (hidden file) :`  Stores API keys (e.g., SERPER API key, Groq API KEY) used by the project.

`requirements.txt :`  Stores all the python libraries. 


## Running the Project
1. **Fork or Clone the Repository::** 

Fork or clone this repository to your local machine using Git.

2. **Install Requirements:**

Install the necessary libraries.

```bash
pip install -r requirements.txt

```

3. **Set Up Environment Variables:**

Create a `.env` file in your project directory and add any required API keys (e.g., SERPER API key, Groq API KEY).

4. **Run the main file:**

```bash
python3 main.py
```

This will initiate the Crew AI workflow and generate a perfect trip plan for you in Markdown and text formats.



## Authors

- [@Bajrangi97](https://github.com/Bajrangi97/my-repo.git)

# Travel-Agents
