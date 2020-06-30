# Online Gallery Viewer

## What is this?
This is an application that can be used to show off some pictures online. Control a player that walks around a virtual art gallery.

A cool feature is that every person that visits your gallery will be visible to the other patrons as they peruse the art.

## Changing images

`/public/scene.json` is a file that contains the environment that the player walks around. Inside that file are base64 encoded images. There are two ways to replace them with your own images.

1. Replace the base64 string with a url to your image
2. Import `scene.json` to [The three.js editor](https://threejs.org/editor/) and change the images using that tool. You can also change the landscape as well.

## Running

1. Clone this repo
2. Make sure you have node and npm installed
	a. `node -v`
	b. `npm -v`
3. Install dependencies
	a. `npm install` 
4. Run the project
	a. `npm start`
5. visit `http://localhost:3000/` in your browser
