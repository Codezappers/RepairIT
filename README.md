# RepairIT

A comprehensive home maintenance tracking app that helps users manage household repairs, appliance warranties, and service reminders. With built-in AI support for troubleshooting and Google Maps integration to locate nearby service providers, RepairIT simplifies home upkeep for homeowners.

## Description

RepairIT is a MERN stack application designed to assist homeowners in organizing their household maintenance tasks. Key features include reminders for upcoming tasks, photo uploads for receipts and warranties, AI-driven repair advice through OpenAI's API, and Google Maps integration to connect users with local contractors. This app aims to save users time and effort by providing all home maintenance tools in a single, easy-to-use interface.

## Getting Started

### Dependencies

* MongoDB
* Node.js
* npm (Node Package Manager)
* OpenAI API key (for repair advice)
* Google Maps API key (for finding local contractors)
* OS: Windows 10 / MacOS / Linux

### Installing

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/RepairIT.git
   cd RepairIT
   ```

2. **Install Backend Dependencies**  
   Navigate to the backend folder and install dependencies:
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**  
   Navigate to the frontend folder and install dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Variables**  
   Create a `.env` file in the root of the backend and add your API keys and MongoDB URI:
   ```plaintext
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   OPENAI_API_KEY=your_openai_api_key
   GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

### Executing program

To run the program, follow these steps:

1. **Start the Backend Server**  
   Open a terminal in the backend folder and run:
   ```bash
   npm run dev
   ```

2. **Start the Frontend Server**  
   Open a terminal in the frontend folder and run:
   ```bash
   npm start
   ```

3. **Access the App**  
   Open a web browser and go to `http://localhost:3000` to access RepairIT.

## Help

For common issues:
* Ensure MongoDB is running, and environment variables are correctly set in the `.env` file.
* For OpenAI and Google Maps integration issues, confirm API keys are valid and permissions are correctly set.
* CORS errors can be resolved by setting up proper headers in the backend.

To view more help options:
```bash
npm run help
```

## Authors

Aden Smith  
[@AdenSmith](https://github.com/yourusername)

## Version History

* 0.2
    * Bug fixes and optimizations for API integrations
    * See [commit change](https://github.com/yourusername/RepairIT/commits/main)
* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

Resources and inspirations:
* [MERN Stack Tutorial](https://www.youtube.com/watch?v=7CqJlxBYj-M) by freeCodeCamp
* [JWT Authentication](https://www.youtube.com/watch?v=mbsmsi7l3r4)
* [React Redux Tutorial](https://www.youtube.com/watch?v=93p3LxR9xfM)
* [OpenAI API Documentation](https://beta.openai.com/docs/)
* [Google Maps API Documentation](https://developers.google.com/maps/documentation)
