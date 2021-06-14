# AO3TextAnalysis
# Fandom Stats and Genre Writing

Note: This project is very very unfinished. As you can see, the bottom section is just me playing around with text parsing and tokenization. It is not meant to be run as a complete project.

#### Yvonne Gonzales
#### Course: Digital Humanities 100 Summer 2021
#### Instructor: Adam Anderson

Digital Humanities project analyzing the language of fanfiction, pulled from the top 3.5k works on Archive of Our Own. Data scraped using this tool: https://github.com/radiolarian/AO3Scraper

# Access the data through Google Drive
Compare and contrast of grand theories: Orem’s self-care deficit theory and roy’s adaptation model

# About the Project
Reading fanfiction feels different than reading traditionally published literature. While fanfiction might come with popular connotations of being romantic or sexual in nature, fanfiction is more of a mode of writing than it is one specific genre. Using Natural Language Analysis and Topic Modeling, I want to figure out what makes fanfiction what it is. What topics are most popular, and how do people write about them? In a future project, I intend to do a similar analysis of popular published literature, but this serves as a starting point for comparing fanfiction to standardized literary forms. Fanfiction has often been studied as a cultural, psychological object, but lacks research as a form of literature, and I want to investigate why it is or why it might not be

# Research Questions
[Primary Research Question.] How is fanfiction written, and how might it be unique? 
Are there any specific names or relationships that show up disproportionately?
What are the percentages of M/M stories, F/F stories, F/M stories, and other gender combinations? What might that say about the genre? 
How popular is fanfiction? How popular are specific fandoms? Does the amount of clicks line up with the amount of likes?

# Proposed Workflow

1.   Scrape Data from Archive of Our Own [DONE]
2.   Import data into Jupyter Notebooks [DONE]
3.   Organize data using Pandas
4.   Clean body text using GenSim and NLTK
      * stemming
      * lemmatization
      * tokenization
5.   Use Gensim to turn tokens in bag of words
6.   Run LDA, organize topics
      * note: this is the step I am least confident on
7.   Start mapping and modeling using Gephi, NetworkX, Altair Viz, whatever makes sense!

# Bio
I am a rising senior at UC Berkeley in the English and History departments, focusing on new media and fan studies. I am fascinated with fanfiction and the cultures, tropes, and norms within it, and will be writing my honors thesis off of the data found in this project.
