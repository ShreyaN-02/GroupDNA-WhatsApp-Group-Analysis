# GroupDNA-WhatsApp-Group-Analysis
A Python and NumPy based analysis of a WhatsApp group chat to uncover participation, activity, vocabulary, and response-time patterns.

# Project Overview
GroupDNA analyzes an exported WhatsApp group conversation and extracts meaningful communication patterns from raw chat data.
The project focuses on understanding:
* Message and participant activity
* Word usage and vocabulary patterns
* Most active days and hours
* Average response gaps
* Longest silent periods
* Participant-level communication patterns
* Overall group behavior

The analysis was built from the ground up using Python fundamentals and NumPy.

# Output


# Project Constraints
This project was intentionally developed under a restricted-tool approach. Where I used only:
* Python fundamentals
* Python built-in data structures
* Lists
* Dictionaries
* Tuples
* Sets
* Loops and conditional statements
* Functions
* File handling
* String operations
* Basic date/time handling
* NumPy

And made this project without:
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* spaCy
* Regular expressions (`re`)
* Ready-made WhatsApp analysis libraries/tools
* External WhatsApp analytics platforms
The purpose of these constraints was to understand and implement the underlying analysis logic rather than relying on high-level data-analysis libraries.

# Seven-Day Build Log

# Day 1 – Chat Parsing
* Loaded the exported WhatsApp chat file.
* Studied the structure of WhatsApp messages.
* Parsed dates, times, participants, and message content.
* Handled system messages and non-standard entries.

# Day 2 – Group Overview
* Calculated total number of messages.
* Counted participants.
* Calculated total words.
* Calculated average words per message.
* Identified the overall date range.

# Day 3 – Activity Analysis
* Calculated participant-wise message counts.
* Analyzed activity by day of the week.
* Analyzed activity by hour.
* Identified the most active day and hour.

# Day 4 – Vocabulary Analysis
* Processed message text.
* Counted word frequencies.
* Identified commonly used words.
* Explored participant-level vocabulary patterns.

# Day 5 – Response & Silence Analysis
* Calculated response gaps between messages.
* Calculated average response time.
* Identified long periods of group inactivity.
* Identified the longest silent gap.

# Day 6 – Participant Patterns
* Combined multiple metrics for individual participants.
* Examined participation and communication behavior.
* Created rule-based participant archetypes from observed patterns.

# Day 7 – Final Analysis
* Combined all analysis modules.
* Generated the final GroupDNA report.
* Checked calculations and outputs.
* Organized the notebook and prepared the project for GitHub.

# Dataset
The project uses an exported WhatsApp group chat:
`hostel_bois.txt`
The dataset contains approximately:
* **3,174 messages**
* **6 participants**
* **31,551 words**
* Date range: **01/04/2024 – 30/05/2024**

 To use this python tool:
 1. Clone the repository
 2. Open the project folder
 3. Install NumPy
 4. Open the notebook
 5. Run the notebook

# Technologies Used
* Python
* NumPy
* Jupyter Notebook

# Learning Outcomes
Through this project, I strengthened my understanding of:
* File handling and data parsing
* Python data structures
* String processing
* NumPy-based computation
* Frequency analysis
* Time-based analysis
* Response-time calculations
* Behavioral pattern identification
* Converting raw data into meaningful insights

**Project:** GroupDNA – WhatsApp Group Analysis
**Built with:** Python + NumPy
**Format:** Jupyter Notebook
