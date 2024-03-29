# Merriam-Webster Vocabulary Definitions
bunnysaini/mw-vocab-def

# Features
This project fetches word definitions from Merriam-Webster Dictionary API and stores them is a CSV file.

## Purpose
If you're learning a set of words for any competitive test to enhance your vocabulary (eg. GRE, TOEFL, IELTS etc.), most of the resources online provide you with a list of words that you have to manually search meanings for. For GRE - [Vince's GRE Compilation and Curation](https://docs.google.com/spreadsheets/d/1K4gS--jbDYbdlqem6Hir3FAwvLB9dFxNCLftE3ePduk/edit#gid=504162758) is a great resource provides only words. With this project, you can provide words and automatically fetch their meaning using the [Merriam-Webster](https://www.merriam-webster.com) API.

## Steps to Use 
- Create a Dev Account on [Merriam Webster Developer Center](https://dictionaryapi.com) and generate an API Key - to fetch word definitions.
  - The API is restricted to 1000 queries per day.
  - The URL used in this project is for the Merriam-Webster's Collegiate Dictionary, if you use another dictionary update the URL and any parts that handle traversing the API response.
- Replace the API Key in code or use as a Secret.
- Run the code with Input file name and path in mind.
- Alternatively declare dictionary in code for a smaller volume of words.
- The instructions in the workbook are pretty thorough and should help navigate it.

## Dev's Note
This project is not optimally developed yet, so you're welcome to suggest changes by raising a PR. I did not want to spend an eternity coding so I developed a boilerplate code for MW's API response. It may not handle their "sense" concept the most efficiently but gives you something to work with.
>I've also added a populated version of Vince's curated word list with **their meanings** incase you have stumbled upon this repo for that, it's under [GRE Words List](https://github.com/bunnysaini/mw-vocab-def/blob/89d89a5679bcf0a83019719d7662c2f19c4942ae/GRE%20Vocab%20List%20-%20Populated/Populated%20GRE%20Word's%20List.xlsx). Feel free to raise a PR and make modifications, if you access this list as it may not be at it's ideal stage yet.
## Data Flow
**Input:** A CSV file with all words in first column and a Header.

<img width="472" alt="input-ss" src="https://github.com/bunnysaini/mw-vocab-def/assets/83510385/6f0631b6-e168-4557-a59f-ea9f733b2bde">


**Output:** A CSV file with the words and their definitions.

<img width="900" alt="output-ss" src="https://github.com/bunnysaini/mw-vocab-def/assets/83510385/77f670d1-d807-45c9-9172-66962fe893ce">
