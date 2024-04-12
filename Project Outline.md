## Project Outline: Helpful Heniu - your personal AI-powered secretary app for summarizing your daily e-mail inbox content. Simple and helpful.

**Project Name:** _Helpful Heniu - summarize incoming mail._

**Start Date:** April 12, 2024

**Anticipated Completion Date:** May 2, 2024

**Project Team:** `[Andrzej Pec as HeadHoncho, null as ProjectPartner]` ***(currently looking for a person to make a duet collab)***

### Project Goal:
To create a web application that allows users to send the content of their received emails for processing by an AI bot, to generate summaries and analyses. The application aims to increase time and information management efficiency by automating the processing and summarization of received message content.

### Initial Project Assumptions:
- Integration with Gmail API to read email content.
- Use of OpenAI API to analyze and generate content summaries.
- Creation of a simple and intuitive user interface.
- Ensuring data security and user privacy.

### Required Features:
- User login and authentication.
- Reading emails within the application.
- Sending content to OpenAI API and receiving responses.
- Displaying summaries in the user interface.
- Basic personalization options for the user in terms of selecting emails to analyze.
- Creating a database to store generated summaries.

### Technologies:
- **Frontend:**
  - **Astro** – "One tool to optimize them all" - the delivery of the website, performance and SEO.
  - **React.js / Next.js** – For dynamic and interactive user interface.
- **Backend:**
  - **Node.js with Express.js** – Robust server-side environment for our app’s backend needs.
- **APIs:**
  - **Gmail API** – Fetch users’ emails for processing.
  - **OpenAI API** – Analyze and generate summaries from the fetched emails.
- **Security:**
  - **OAuth 2.0** – Secure authorization for accessing user data from third-party services.
  - **HTTPS** – Secure connections between the client and server.
- **Database:**
  - **MongoDB** – For its flexibility and scalability.

### Learning Plan:
- Learning advanced aspects of React.js and/or Next.js - choosing the right tool for the frontend.
- Considering the use of alternative sources to OpenAI for reading and interpreting content through AI (huggingface).
- Enhancing understanding of connecting applications with external APIs.
- Practical use of existing knowledge about SQL query creation.
- Understanding and implementing secure methods of authentication and communication in web applications.

### Preliminary Schedule:
- **Research Phase (April 12 - April 15)** – Learning necessary technologies and preparing the environment. **Asking experts for their opinions on design choices and planning the timing of the next steps.**
- **Design Phase (April 17 - April 20)** – Designing the application architecture and user interface.
- **Implementation Phase (April 22 - April 25)** – Creating a working prototype of the application.
- **Testing Phase (April 27 - April 30)** – Refining the interface appearance and iterative preliminary testing.
- **Deployment Phase (May 2 onwards)** – Publishing the application and monitoring its performance.

### Possibilities for Further Development (Stage 2):
- Increase the range of settings for reading emails by AI and the way results are presented (possibility to set e.g., the temperature for the bot's output).
- Migrate the application to a mobile environment using Flutter or React Native.
- Collecting user feedback and implementing interesting suggestions to improve functionality.
