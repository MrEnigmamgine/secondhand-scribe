![Spellcard](spellcard.svg)
# Secondhand Scribe

Secondhand Scribe is a tool to help DMs and players take notes for their TTRPG campaigns.

It works by processing audio recordings of your sessions. Using AI to transcribe your voices into text, it then employs a number of natural language processing techniques to extract useful summaries and notes about your session.


## Work in Progress
You'll notice that there isn't a lot of code here.  That's because the project is a work in progress and is not yet in a usable state.  I am currently researching solutions and designing processes to make this dream a reality.

If you'd like to follow the progress of my research I invite you to the speghetti-code [hosted here](https://github.com/MrEnigmamgine/Audacle).  As I settle on processess and solutions they will be added here and integrated into the tool.


## Design Goals
### Opensource and local where possible
I want this tool able to run locally on an average computer.  Therefore the use of API services should be kept to a minimum.  Unfortunately, some features might require the use of a LLM (Large Language Model) which would be unreasonable for most people to run on their own computer.  Features that requre the use of an outside API should be clearly labeled and configurable.

### Webapp GUI
Since at it's core this tool involves the collection and processing of data (audio & text), the data should be presentable and managable in a useful and accessible way.

### Efficiency and Performance
Many of the processes employed by this tool will require a lot of CPU and GPU computing.  Therefore the data should be processed and stored in a way that minimizes the computing cost, especially for AI training and fine-tuning pipelines.

### User-friendly Data Science
This tool will rely heavily on Data Science methodologies.  The UI should guide the user into making good choices when using their own data while explaining some of the pitfalls that might occur.