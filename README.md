# Emsi Interview Project by Michael Singhurse

## Initial thoughts before beginning
The project seems pretty straightforward. I believe I understand all the
requirements. I think there will be two primary challenges for me:
1. The time limit. I'm not sure I'll be able to meet all the requirements in 8
   hours.
2. The line graph. I've never used a front-end charting library, so I'm going to
   have to research the options, decide on one, quickly learn the API, and then
   try to implement something.

I'll take the following steps in building this project:
1. Develop the HTML and CSS with fixed/hard-coded job data (no API calls). I'll
   do this first to get the UI to look right.
2. Set up the server. I'll use Node and Express. It'll do two things. One, serve
   up the static HTML, CSS, and JS files. Two, respond to a get request for job
   data by responding with the JSON object provided. I'll just store the JSON
   file on disk, read it into memory, and send it as a response body.
3. Handle the dynamic job data on the client side. If I had more time, I would
   probably use React to build out components. I don't want to spend a lot
   of time setting up a React project, however, so I'm going to try client-side 
   HTML templates. I'm most familiar with Handlebars.

OK, here goes. At the end of 8 hours I'll report below on what I was able to
accomplish.

## Final thoughts after finishing

I was able to accomplish all the project goals except for the line chart/graph.
I saved that for last as it was something I was unfamiliar with, but I ran out
of time and didn't get to it.

If I had more time, these are the additional steps I would take:

1. Install the line graph.
2. Replace the Handlebars templates with React components.
3. Refine and improve the CSS styling to more closely match the mockup. 

## Deliverables
### Link to the GitHub repo

### Screenshots of the final project

#### Chrome
![screenshot-chrome.png](screenshot-chrome.png)

#### Firefox
![screenshot-firefox.png](screenshot-firefox.png)

### Instruction for running the code and viewing the web page
1. Download the project files.
2. Make sure you have Node and npm on your machine.
3. Run `npm install` at the command line.
4. Run `npm start` at the command line.
5. The app will be available at localhost port 3000.


