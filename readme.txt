1. create .env file

and keep these inside it 

GEMINI_API_KEY="your api key here"
LINKEDIN_EMAIL="your linkedin email"
LINKEDIN_PASSWORD="your linkedin password"

replace those values with your creds :)


2. it will do linkedin login only once later it will create cookies and manages session so auto apply makes easy

3. install packages


pip install \
    google-generativeai \
    selenium \
    webdriver-manager \
    beautifulsoup4 \
    pandas \
    pymupdf \
    requests \
    lxml \
    openpyxl \
    tqdm \
    python-dotenv \
    numpy
    
    if any installation error , install that package :)


4. automation_testing contains all code , if any error comes you can check individual notebook for reference



PS:

Indeed auto apply is in progress may not be completed by now

Other sites scraping is also in progress


For Demo :


1. we are extracting resume 
2. scraping jobs from indeed and linkedin
3. auto applying "easy apply" jobs in linkedin

there were performance lack(taking more time ) we need to optimize them so we'll do it in full version


 








