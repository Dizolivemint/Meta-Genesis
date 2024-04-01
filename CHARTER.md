# Project Charter: Meta-Analysis Research Application

## Project Overview
The Meta-Analysis Research Application aims to provide users with a platform to query research articles based on specific questions and produce meta-analyses to answer those questions. The application will search the NCBI (PubMed) database for relevant articles, store them in a vector database, and pass the data to a Large Language Model (LLM) API endpoint for meta-analysis. The results will be published to a database and displayed in a user-friendly format on the application's frontend.

## Objectives
- Develop a user-friendly frontend application for querying research articles and displaying meta-analysis results.
- Implement a backend system to search and store articles from NCBI.
- Integrate with an LLM API endpoint for meta-analysis.
- Create a real-time newsfeed of meta articles for users to browse and search using a fuzzy search algorithm.
- Provide users with the ability to create meta articles if none exist for their query.

## Key Features
1. Query Research Articles: Users can input specific questions or topics to search for relevant research articles.
2. Meta-Analysis Generation: Articles found in the query are passed to an LLM API endpoint for meta-analysis.
3. Real-Time Newsfeed: Display meta articles in a newsfeed format, updated in real-time.
4. Fuzzy Search Algorithm: Allow users to search for meta articles using a fuzzy search algorithm for enhanced discoverability.
5. Create Meta Articles: Users can create meta articles if none exist for their query, contributing to the database of meta analyses.
6. Article Reading List: Provide users with a list of articles found in the query for reading while the meta-study is being produced.
7. Notifications: Notify users via a snack bar and device notifications (if enabled) once the meta-analysis is produced.

## Key Questions for Meta-Analysis
1. Publication Date: When was the paper published?
2. Sample Size: What is the sample size?
3. Study Methodology: Is it a randomized control trial?
4. Funding Source: How was the study funded? Were funds from commercial sources?
5. Key Research Question: What was the key question being studied?
6. Key Findings: What were the key findings related to the key question?

## Team Members
1. Miles Exner
2. John McCants

## Required Resources
- Figma Designers: We are looking to onboard Figma designers to help with the UI/UX design of the application.

## Timeline
- [Insert Timeline Here]

## Budget
- [Insert Budget Here]

## Risks and Mitigation
- Data Privacy: Ensure all user data is securely stored and comply with data protection regulations.
- API Dependency: Have backup plans in place in case the LLM API endpoint becomes unavailable.
- User Adoption: Implement user feedback mechanisms to improve the application's usability and adoption rate.

## Stakeholders
- Users: Researchers, students, and anyone interested in accessing meta-analyses of research articles.
- Development Team: Responsible for designing, developing, and maintaining the application.
- Figma Designers: Responsible for creating the UI/UX design of the application.

## Conclusion
The Meta-Analysis Research Application aims to provide a valuable resource for users to access and contribute to meta-analyses of research articles. By leveraging NCBI, LLM API, and a user-friendly frontend, the application seeks to enhance the accessibility and usability of meta-analysis in the research community.