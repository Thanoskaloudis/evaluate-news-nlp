# Evaluate A News Article with Natural Language Processing

This project goal is to build a web tool that allows users to run Natural Language Processing (NLP) on articles or blogs found on other websites. When a user submits a URL of an article, the web page then dispalys sentiment analysis returned from [meaningcloud API](https://www.meaningcloud.com/products/sentiment-analysis), based on the contents of the article or blog.

## Installation Steps
1. Make sure Node and npm are installed from the terminal. Then run:

    ```
    npm install
    ```

2. You need tosign up for an API key at [meaningcloud.com](https://www.meaningcloud.com/developer/create-account).

3. Configure environment variables using dotenv package.
	* Create a new `.env` file in the root of your project.
	* Fill the `.env` file with your API key like this:
	```
	API_KEY=**************************
	```

4. Start the project.

    ```
    npm run build-prod
    ```
    ```
    npm run start
    ```

5. Open browser at http://localhost:8081/
