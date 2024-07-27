# YouTube-Data-Collection-and-Analysis
This is aiming in gathering and examining data from YouTube to gain insights into video trends, audience engagement, and content performance. 
This project utilizes the YouTube Data API to collect data on video statistics, such as views, likes, comments, and more. Using Python libraries like pandas and matplotlib, the project performs data cleaning, visualization, and analysis to identify patterns and trends.
To collect data from YouTube, it's important to clearly define the type of data you need. In this case, we'll focus on gathering data about trending videos to analyze what contributes to a video's popularity on YouTube.

Here's how you can set up the YouTube Data API to collect this data:

1. **Access the Google Cloud Console:**
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).

2. **Create a New Project:**
   - Click on the project drop-down menu at the top of the page and select "New Project."
   - Enter a project name and click "Create."

3. **Enable the YouTube Data API:**
   - In the Google Cloud Console, navigate to "APIs & Services" > "Library."
   - Search for "YouTube Data API v3" and select it.
   - Click "Enable" to activate the API for your project.

4. **Create API Credentials:**
   - Go to "APIs & Services" > "Credentials."
   - Click "+ CREATE CREDENTIALS" and choose "API key."
   - Copy the generated API key for use in your project.

Once we collect the data about the top 200 trending videos on YouTube,we will be next fetching details of the top 200 trending videos in the US, iterating through the API’s paginated responses to collect video details such as title, description, published date, channel information, tags, duration, definition, captions, and various engagement metrics like views, likes, and comments. 

Post this we will be cleaning the data and then visualize the data.
