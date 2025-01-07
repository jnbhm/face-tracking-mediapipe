# Simple face landmarks detection with MediaPipe

This is an example how to use the face landmark detection model with MediaPipe. Find the full description of the model [here.](https://ai.google.dev/edge/mediapipe/solutions/vision/face_landmarker)

To run this project you'll need to have [Node.js](https://nodejs.org/en) installed on your machine. The project was set up with [vite](https://vite.dev/).

## Dev

To start this project run the following command in the root folder of the project.

```bash
npm install
```

Run the dev task to see your changes live.

```bash
npm run dev
```

### Use the detections

To use the detection you can access the `detections` object in the `processResults` function. You can find this function in `src/js/script.js`

## Build

To build this project run the following command:

```bash
npm run build
```

The built project will be in the dist folder.
