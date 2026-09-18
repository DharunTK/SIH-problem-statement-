# Smart India Hackathon Workshop

## Date:
18-09-2026

## Register Number:
21222524003938

## Name:
Dharun T K

## Problem Title

**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

## Problem Description

### Background

Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations.

Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections.

### Description

The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities.

The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks.

### Key Challenges

- Updating navigation information in real time
- Ensuring accuracy of station maps
- Supporting different types of passengers
- Providing accessible routes
- Handling changes in station layouts
- Providing simple and clear directions

### Expected Solution

The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station.

The system should include:

- A mobile application with interactive 3D maps
- Step-by-step navigation
- Digital kiosks with touch-screen interfaces
- Voice-guided navigation for visually impaired passengers
- Accessibility-friendly routes
- Regular updates to station layouts and facility locations
- Integration with existing railway applications and services

The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creator's Organization

**Ministry of Railway**

# Idea

## RailNav 3D – Smart Railway Station Navigation System

RailNav 3D is a smart indoor navigation system that helps railway passengers easily find platforms, ticket counters, restrooms, food courts, waiting areas, lifts, escalators, exits, and other facilities inside railway stations.

The application provides an interactive 3D map and step-by-step navigation from the passenger's current location to the selected destination.

The system also supports accessibility features such as wheelchair-friendly routes, lift-based navigation, and voice-guided navigation for visually impaired passengers.

### Key Features

- Interactive 3D railway station map
- Indoor navigation
- Step-by-step directions
- Facility search
- Wheelchair-accessible routes
- Lift and escalator navigation
- Voice-guided navigation
- Digital kiosk support
- QR code route sharing
- Real-time station updates
- Emergency navigation
- Mobile and web support

# Proposed Solution / Architecture Diagram

```text
                     PASSENGER
                         |
             +-----------+-----------+
             |                       |
             v                       v
       MOBILE / WEB APP        DIGITAL KIOSK
             |                       |
             +-----------+-----------+
                         |
                         v
                  BACKEND SERVER
                Node.js + Express
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
   NAVIGATION        DATABASE     ACCESSIBILITY
     ENGINE          MongoDB         MODULE
          |              |              |
          +--------------+--------------+
                         |
                         v
                 ROUTE CALCULATION
                  A* / DIJKSTRA
                         |
                         v
                3D MAP + DIRECTIONS
                         |
                         v
                 PASSENGER DESTINATION
```

### Working Process

```text
Select Station
      |
Select Current Location
      |
Search Destination
      |
Select Accessibility Requirement
      |
Calculate Route
      |
Display Route on 3D Map
      |
Provide Step-by-Step / Voice Directions
      |
Reach Destination
```

# Use Cases

### 1. Platform Navigation

Passengers can search for a platform and receive step-by-step directions from their current location.

### 2. Facility Navigation

Passengers can locate:

- Ticket counters
- Platforms
- Restrooms
- Food courts
- Waiting areas
- Lifts
- Escalators
- Information counters
- Entrances and exits

### 3. Wheelchair Navigation

The system provides routes that avoid stairs and prioritize accessible paths and lifts.

### 4. Voice Navigation

Visually impaired passengers can receive voice-based navigation instructions.

Example:

```text
"Continue straight for 20 metres."
"Turn left at the information counter."
"Take the lift to the next floor."
"Platform 3 is ahead."
```

### 5. Digital Kiosk

Passengers can use touch-screen kiosks installed throughout the railway station to search for facilities and destinations.

### 6. QR Code Navigation

The kiosk can generate a QR code for the selected route. Passengers can scan it and continue navigation on their mobile phone.

### 7. Emergency Navigation

Passengers can use the system to find emergency exits and other important safety locations.

# Technology Stack

### Frontend

- React.js
- Vite
- HTML5
- CSS3
- JavaScript
- Three.js
- WebGL

### Backend

- Node.js
- Express.js
- REST API

### Database

- MongoDB
- MongoDB Atlas

### Navigation

- Python
- A* Algorithm
- Dijkstra's Algorithm
- Graph Data Structures

### Accessibility

- Web Speech API
- Text-to-Speech
- Voice Commands

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Postman

### Deployment

- Vercel
- Render
- MongoDB Atlas

# Dependencies

## Frontend Dependencies

```text
react
react-dom
react-router-dom
three
@react-three/fiber
@react-three/drei
axios
```

## Backend Dependencies

```text
express
cors
mongoose
dotenv
body-parser
```

## Development Dependencies

```text
vite
nodemon
```

## Python Dependencies

```text
numpy
networkx
```

# Expected Outcome

The proposed system will provide an easy-to-use navigation solution for railway stations.

It will help passengers:

- Find facilities quickly
- Navigate between different areas
- Reduce confusion and walking time
- Access wheelchair-friendly routes
- Use voice-based navigation
- Navigate using digital kiosks
- Receive updated station information
- Find emergency exits efficiently

# Future Scope

- BLE-based indoor positioning
- Wi-Fi-based indoor positioning
- Augmented Reality navigation
- AI-powered passenger assistance
- Multilingual voice navigation
- Crowd-density-based route optimization
- Emergency evacuation navigation
- Live railway API integration
- Computer vision-based location detection
- AI-based congestion prediction

# Project Status

**Prototype / Development Phase**

# Problem Details

**Problem ID:** SIH 1710

**Problem Title:** Enhancing Navigation for Railway Station Facilities and Locations

**Organization:** Ministry of Railway

**Domain:** Smart Transportation / Artificial Intelligence / Navigation
