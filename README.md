# Rider - Real-Time Package Tracker

Rider is a simple and responsive web application that allows users to track their packages in real time using the browser's geolocation API and Mapbox GL JS.
![image](https://github.com/user-attachments/assets/10ab62fe-8850-4435-9c41-fc453503fe9e)


## 📦 Features

- 🗺️ Real-time geolocation tracking using Mapbox
- 📍 Custom marker display for location indication
- 🔒 Simple UI/UX with clean design and navigation
- 📱 Responsive layout with support for modern browsers
- ⚙️ Built using HTML, CSS, and JavaScript (ES6 modules)

## 📂 Project Structure
Rider/ 
├── index.html         # Main HTML structure
├── assets/ 
│   ├── style/ 
│   │ └── index.css    # Styling for layout and components 
│   └── script/ 
│     └── app.js       # JavaScript logic for geolocation and map interaction

## 🚀 How It Works

1. User lands on the homepage and clicks the "Track" button.
2. The browser requests location permission.
3. If granted, the map recenters to the user's current location and displays a marker.
4. The app disables map controls to provide a focused experience.

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Mapbox GL JS** for map rendering and geolocation

## 📌 Setup Instructions

1. Clone this repository or download the files.
2. Replace the Mapbox access token in `app.js` with your own from [Mapbox](https://www.mapbox.com/).
3. Open `index.html` in your preferred browser.

> **Note**: Ensure geolocation is supported and enabled in your browser.

## 👤 Author

**Ayomide Boye-Ogundiya**  
📍 Winnipeg, Canada  
📧 boyeayomide@gmail.com

## 📄 License

This project is licensed under the MIT License.

