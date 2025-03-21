# StreamAnalyzerSimulate ----- READ -----

A web-based interface for the YouTube Stream Analyzer application that provides real-time sentiment analysis of YouTube live stream comments.

**Link:** [StreamAnalyzer](https://streamanalyzer-fyc2aafqgyavedc2.spaincentral-01.azurewebsites.net/)

## Project Overview

StreamAnalyzer.WEB serves as the frontend for the Stream Analyzer system, offering a user-friendly interface to analyze YouTube live stream comments in real-time. The application connects to a backend API service that processes YouTube comments and returns sentiment analysis results through a streaming connection.

**Note:** The AI prediction of comments is not completed yet. Currently, the API introduces a 2-second delay to simulate the AI prediction.

### Key Features

- Real-time comment analysis using Server-Sent Events (SSE)
- Sentiment analysis visualization for YouTube stream comments
- Live statistics and data aggregation
- Responsive design using React and Bootstrap

## Technical Architecture

### Frontend

- **Framework**: React with TypeScript
- **UI Components**: React Bootstrap
- **Styling**: SCSS with Bootstrap integration
- **Bundling**: Webpack

### Backend

- **Server**: Node.js with Express
- **API Integration**: Proxy middleware to StreamAnalyzer API
- **Real-time Updates**: Server-Sent Events (SSE)
- **Deployment**: Azure App Service

### API Service

- **Framework**: ASP.NET 9
- **Communication**: Server-Sent Events (SSE) for real-time data streaming
- **Current Implementation**: Simulates AI sentiment analysis with a 2-second delay
- **Future Development**: Actual AI-based sentiment analysis to be implemented
