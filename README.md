# 360VisionDual

360VisionDual is a web application that allows you to compare two 360° panoramic images interactively using a slider. This tool is perfect for showcasing before-and-after scenes, comparing environments, or visualizing changes in virtual spaces.

## Features

- **Dual 360° Panoramic Views**: Seamlessly compare two panoramic images side-by-side.
- **Interactive Slider**: Drag the slider to control how much of each image you want to reveal.
- **Orbit Controls**: Full 3D view control with zoom and pan functionality.
- **Fullscreen Mode**: Experience the panoramas in fullscreen for an immersive experience.

## Usage

1. Upload two sets of cubemap images for both panoramas.
2. Pan and zoom the view using mouse or touch gestures.
3. Drag the central slider to compare the two panoramic views interactively.

## Installation

To set up and run the 360VisionDual project locally, follow the instructions below:

#### Prerequisites
Ensure that you have Node.js installed on your system.
Use any modern web browser (Chrome, Firefox, etc.) or set up a local development server.
#### Step-by-Step Setup
 **Clone the repository:**
   

   git clone https://github.com/oyersen/360VisionDual.git
   cd 360VisionDual
   npm install
   npm start

## File Structure
```bash
360VisionDual/
│
├── public/
│   ├── panorama_1/  # First panoramic images (Cubemap: px, nx, py, ny, pz, nz)
│   └── panorama_2/  # Second panoramic images (Cubemap: px, nx, py, ny, pz, nz)
├── src/
│   ├── js/          # JS logic for rendering and controls
│   ├── css/         # Styling files
├── index.html       # Entry point
├── package.json     # Project dependencies and scripts
└── README.md        # Project documentation
```
## Technologies Used
#### Three.js: A JavaScript 3D library that makes WebGL simpler to use.
#### HTML5 and CSS3: For structuring and styling the web app.
#### JavaScript Modules: ES6+ syntax for clean and maintainable code.
#### How to Contribute
#### Fork the repository.
#### Create a new branch for your feature (git checkout -b feature-branch).
#### Commit your changes (git commit -m 'Add some feature').
#### Push to the branch (git push origin feature-branch).
#### Open a pull request.
# License
#### This project is licensed under the MIT License. See the LICENSE file for more details.
