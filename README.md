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
============================================================
              GROUPDNA – WHATSAPP GROUP ANALYSIS
============================================================

1. GROUP OVERVIEW
------------------------------------------------------------
Group Name          : Hostel Bois 4ever
Total Participants  : 6
Total Messages      : 3174
Total Words         : 31551
Average Words/Msg   : 9.94
Date Range          : 01/04/2024 to 30/05/2024

Participants:
   Rahul : 953 messages ( 30.03 %)
   Priya : 718 messages ( 22.62 %)
   Karan : 354 messages ( 11.15 %)
   Neha : 635 messages ( 20.01 %)
   Aman : 490 messages ( 15.44 %)
   Vikas : 24 messages ( 0.76 %)

2. MOST ACTIVE DAY & HOUR
------------------------------------------------------------
Most Active Day    : Wednesday
Most Active Hour   : 18:00
Messages on Day    : 483
Messages at Hour   : 248

3. TOP WORDS
------------------------------------------------------------
   hai : 249
   bhai : 160
   one : 157
   had : 151
   started : 150
   no : 146
   scene : 145
   entire : 145
   please : 141
   yaar : 139

4. ACTIVITY SUMMARY
------------------------------------------------------------
Peak activity occurs on Wednesday at 18:00.
The activity matrix contains 3174 messages.
This confirms that all parsed messages
were included in the activity analysis.

5. RESPONSE TIME ANALYSIS
------------------------------------------------------------
Average Response Gap : 27.2 minutes
Longest Silent Gap   : 5.98 hours

6. PERSONALITY ARCHETYPES
------------------------------------------------------------
Personality archetypes are assigned based on
message activity and communication patterns.
   Rahul : The Most Active Member
   Priya : The Most Active Member
   Karan : The Active Participant
   Neha : The Regular Contributor
   Aman : The Regular Contributor
   Vikas : The Silent Observer

============================================================
                    FINAL SUMMARY
============================================================
GroupDNA analyzed the WhatsApp group using
Python fundamentals, NumPy and datetime.

Key Findings:
- Total messages analyzed : 3174
- Total participants      : 6
- Most active day         : Wednesday
- Most active hour        : 18:00
- Total words             : 31551
- Average words/message   : 9.94

============================================================
                  END OF REPORT
============================================================


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
