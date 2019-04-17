# ECB-press-conference-transcript-web-crawler

Nowadays, sentiment is one of the biggest or newest pathways in financial statistics, especially for modelling returns and volatilities. This repository provides a tool to automatically download all European Commercial Bank (ECB) Press Conference transcripts from 1998 until present. These documents are downloaded directly from the official web site of ECB, https://www.ecb.europa.eu/press/pressconf/2019/html/index.en.html

Because all documents are scraped in the webpage, they are originally of the .HTML form, and of .TXT form after downloading.
Notice that, these documents are really crude and raw, therefore, some further analysis is needed to extract information from these files, and sentiment analysis from this dataset is still a long way to go.

As mentioned above, the txt files downloaded by the web crawlers are still of HTML form, which means that they are pretty crude and messy. Therefore, further cleaning of this data is mandatory before thinking about other steps. The notebook "HTML cleaner" provides tool to clean the HTML data and return the pure transcript, (you may find an example with "Before_cleaning" and "After_cleaning" files). Notice that, the code in HTML cleaner is specialized only in my PC. That means you may change the working directory or so to be compatible with your working machine.

Now, everything is clean and have fun with it!!!
