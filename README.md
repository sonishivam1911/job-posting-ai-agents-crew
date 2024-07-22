# AI Crew for Jobs postings


## Introduction
This project aims to automate the process of coming up with an Jobs postings.

## Running the Script
- **Configure Environment**: Copy ``.env.example` and set up the environment variables for OpenAI and [Serper](https://serper.dev/).
- **Install Dependencies**: Run `pip install -r requirements.txt`.
- **Execute the Script**: Run `python main.py` and input your idea.

## Details & Explanation
- **Running the Script**: Execute `python main.py`` and input the requested information when prompted. The script will leverage the CrewAI framework to create the job posting for you
- **Key Components**:
  - `./main.py`: Main script file.
  - `./tasks.py`: Main file with the tasks prompts.
  - `./agents.py`: Main file with the agents creation.
  - `./job_description_example.md`: Example of a job description the crew will use as inspiration.
