# Web-scrapping-using-Python--Part-2

I will scrape directory information from the Management Science and Information Systems department at OSU (https://business.okstate.edu/directory/index.html?d=Department%20of%20Management%20Science%20%26%20Information%20Systems). I will scrape the following data for faculty and lecturers and convert it into a data frame:

Name

Title (assistant, associate, full, etc)

Office address

Phone number

Email address

Each bulleted item above needs to be a column in the data frame, Use rvest to scrape the data.

Additionally, I will create both CSS selectors as well as XPath selectors for each bulleted item. Thus, you will have 6 CSS selectors and 6 XPath selectors.

Lastly, I will export the data frame as a tab-delimited file with a .txt extension, will check data frame to ensure no duplicates (this can be a problem because of your CSS selector). 

Using regular expressions, separate the first name and last name. Will create two additional columns in your data frame, one for first name and another for last name. Populate those columns with the appropriate data. I will have the following columns:

Name

First Name

Last Name

Title (assistant, associate, full, etc)

Office address

Phone number

Email address
