# Solving murder mystery using SQL
There's been a Murder in SQL City!This project involves solving a murder mystery about a murder that occured on Jan. 15, 2018, in SQL City, and the detective needs your help to gather information, analyze clues, and draw conclusions to solve the case.
You can check out this website for detailed information about the murder and the necessary attributes:(https://mystery.knightlab.com/)
## Prerequisites
* Python 3.x
* sqlite3
## Project Structure
1. Retrieve Crime Scene Report
Task: Run a query to retrieve the crime scene report for the murder that occurred on Jan.15, 2018, in SQL City. Gather all available details from the report.

2. Witness Personal Details
Task: Check the personal details of witnesses involved in the case. Retrieve their names, addresses, and any other relevant information.

3. View Witness Interviews
Task: Access the recorded interviews of witnesses conducted after the murder. Gather insights into their statements and potential clues.

4. Check Gym Database
Task: Investigate the gym database using details obtained from the crime scene report and witness interviews. Look for any gym-related information that might be relevant.

5. Check Car Details
Task: Examine the car details associated with the crime scene. Retrieve information about the vehicles present during the incident.

6. Personal Details
Task: Identify and collect personal details mentioned in the previous query. This includes names, addresses, and any additional details.

7. Membership Status at the Gym
Task: Determine who is identified in the previous query as a member of the gym. Utilize the gym database to confirm their membership status.

8. Analyze and Draw Conclusions
Task: Analyze the collected data, including crime scene reports, witness interviews, gym records, and car details. Draw conclusions or hypotheses based on the information available.

9. Document Findings
Task: Document your findings and any insights gained from the SQL investigation. Summarize the key details that lead you to your conclusions.

10. Prepare a Report
Task: Prepare a detailed report for the detective, summarizing the events, suspects, and your conclusions. Present the evidence and rationale behind your findings.

11. Reflect on the Investigation
Task: Reflect on the investigative process. What challenges did you encounter, and how did you overcome them? Share your reflections on the case-solving experience.

# Web Scraping Books information
This project involves scraping book information from a website using Python, Requests, and BeautifulSoup.
## Overview
The goal of this project is to extract all the necessary data about books from multiple pages of a website, organize the data, and store it for further analysis.
The website to be scraped:(https://books.toscrape.com/)
## Prerequisites
* Python 3.x
* Required Python libraries: requests, beautifulsoup4, pandas
## Code Explanation 
* url: Contains the base URL for the pages to be scraped.
* Scraping Loop: Iterates through the specified number of pages, sends HTTP requests, and retrieves book details.
* Data Extraction: Details like image, title, rating, price, and link are extracted from each book on the page.
* Data Storage: Extracted data is stored in a list of lists (books), which can be further used for analysis or saved in a file.
