# :snowflake: Scraping GitHub

## Web Scraping 
- Web Scraping refers to the extraction of data from a website. 
- This information is collected and then exported into a format that is more useful for the user , like a spreadsheet or an API.

![image](https://user-images.githubusercontent.com/96012488/216526319-8981f38f-84f4-44e2-ad74-6012b9747514.png)


## About the Project

- We're going to scrape https://github.com/topics.
- We'll get a list of all the topics. For each topic, we'll get topic title, topic page URL and topic description.
- For each topic, we'll get the top 25 repositories in the topic from the topic page.
- For each repository, we'll grab the repo name, username, stars and the repo URL.
- For each topic, we'll create a CSV file in the following format:

````
Repo name,Username,Stars,Repository URL
three.js,mrdoob,88500,https://github.com/mrdoob/three.js
react-three-fiber,pmndrs,21100,https://github.com/pmndrs/react-three-fiber

````

*I've used Python for this project. You can check out the **Jupyter notebook** for the project [here]()!*
    
