### AI-Agent Swarm

This README has been updated to include instructions for setting up a virtual environment, activating it, and running the script. It provides guidance on editing, setting up, and using the Python script with functionalities for web scraping, summarization, and making Google searches using various APIs and models.

#### Prerequisites

1. Python 3.6 or higher installed on your system.

#### Environment Setup

1. **Create a Virtual Environment**: 
   This isolates your Python/Django setup on a per-project basis.
   - Create a virtual environment using:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - For Linux or macOS:
       ```bash
       source venv/bin/activate
       ```
     - For Windows:
       ```bash
       venv\Scripts\activate
       ```

2. **Install Dependencies**:
   - Install the required libraries using the `requirements.txt` file. Run the command:
     ```bash
     pip install requests beautifulsoup4 dotenv langchain autogen
     ```

3. **Environment Variables**: 
   - Set up `BROWSERLESS_API_KEY` and `SERP_API_KEY` in a `.env` file in the script's directory:
     ```
     OPENAI_API_KEY=your_api_key
     BROWSERLESS_API_KEY=your_browserless_api_key
     SERP_API_KEY=your_serper_api_key
     ```

4. **Configuration Files**: 
   - Ensure the presence of a `OAI_CONFIG_LIST` JSON configuration file as required by the script.

#### Editing the Script

1. **Adding/Modifying Functions**: Define or edit functions in the script, ensuring proper documentation.

2. **Updating Environment and Configurations**: Edit `.env` file and configuration files as needed.

3. **Integrating with Other APIs**: Add necessary request code for additional API integrations.

4. **Error Handling**: Add robust error handling for increased resilience.

#### Running the Script

1. **Activate Virtual Environment**: 
   - Ensure that the virtual environment is activated before running the script.

2. **Start the Bot**: 
   - Use the following command to start the bot:
     ```bash
     python bot/main.py
     ```

#### Notes

- Handle API keys and configurations carefully to maintain script functionality.
- Test changes in a controlled environment before deployment.

This README provides comprehensive instructions for customization and usage of the script. Enjoy coding!
