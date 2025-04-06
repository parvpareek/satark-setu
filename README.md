# Satark Setu

A real time crime reporting app:

App demo: 
Law enforcement dashboard demo: https://youtu.be/rkJsrF5KoOA

## Overview

The Real Time Crime Reporting App allows citizens to report crimes instantly using multiple channels. It features a multilingual speech interface, video uploads, and form-based reporting. Users can view reports on an interactive map, receive notifications for nearby incidents, and join community discussions. Special safety features like Satark Saheli and a Panic Mode enhance personal security and emergency response.

## Key Features

- **Real-Time Crime Reporting**
  - **Multilingual Speech Reporting:** Utilize speech-to-text technology for 22 Indic languages (including Hindi, Gujarati, Marathi, Bengali, etc.) powered by the IndicConformer-Multilingual model by AI4Bharat.
  - **Video Reporting:** Capture and upload video evidence directly from your device.
  - **Form-Based Reporting:** Fill out detailed forms to report incidents when speech or video isn’t convenient.
  
- **Map Integration**
  - **Interactive Map:** View live crime reports on a map integrated with OpenStreetMap, making it easier to spot trends and clusters in real time.
  
- **Neighborhood Notifications**
  - **Real-Time Alerts:** Receive instant notifications about crime reports within a defined neighborhood radius.
  
- **Community Forum**
  - **Knowledge Sharing:** Engage in discussions about events, safety measures, and community strategies in an integrated forum.
  
- **Safety Features**
  - **Satark Saheli:** A dedicated feature for women travelling at night to share their real-time location with trusted contacts via messaging integration.
  - **Panic Mode:** Activate a panic button that streams audio and video in real time directly to the authorities during emergencies.

## Technologies Used

- **Mobile App:** Developed in Flutter with integration of OpenStreetMap for real-time mapping.
- **Speech Recognition:** Powered by AI4Bharat's IndicConformer-Multilingual model for accurate multilingual speech-to-text conversion.
- **Backend Dashboard:** Built with the ERN (Express, React, Node) stack.
- **Database:** Managed using Supabase Postgres for scalable and secure data storage.

## Setup & Installation

### Prerequisites

- **Flutter SDK:** For building and running the mobile app.
- **Node.js & npm:** For setting up the backend dashboard.
- **Supabase Account:** For database management with Postgres.
- **ERN Stack Environment:** Pre-configured for the dashboard.
