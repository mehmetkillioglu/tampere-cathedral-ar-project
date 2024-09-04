# Tampere Cathedral AR project

This project contains the source code that was used in a thesis work. This software uses [AR.js](https://github.com/AR-js-org/AR.js) library to create an augmented reality experience with a web browser. This project was created for the Tampere Cathedral.

Some of the artwork from Tampere Cathedral has been trained using [Carnaux/NFT-Marker-Creator](https://github.com/Carnaux/NFT-Marker-Creator). Those are added as NFT markers to track using AR.js. Then those NFT markers are linked to a html page which is shown inside the popup.

## How to run the project
Simply run a web server with the project files. The index page will load the connected video camera and wait for one of the trained images to be pointed. Once it detects, a half-window pop-up will appear containing the details of the shown image, in this case, the artwork in the Tampere Cathedral. High resolution image of the artwork will appear, and extra historical information and facts.

If the image is detected, but then lost for 5 seconds, the popup will disappear. User has the option to click on top banner in the popup to expand the content which wont disappear until user closes it.

# Switching cameras and resolution
- Top left selection will list the available cameras available. Sometimes it automatically switches to front or fish eye camera. The best performance is achieved with the back main camera.
- Top right, there are three buttons to switch between 480p, 720p, and 1080p resolutions.
- Below those resolution buttons, there are 1x, 2x, 5x buttons to toggle zoom, in case the artwork of interest is far away.

# Try live version
The live version of the project can be found

[Tampere Cathedral AR project - Onrender](https://tampere-cathedral-ar-project.onrender.com/)

