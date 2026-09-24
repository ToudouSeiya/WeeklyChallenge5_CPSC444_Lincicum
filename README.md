# WebGL Weekly Challenge 5
Morgan Lincicum

A static WebGL lighting scene built with plain HTML, GLSL, and JavaScript.

My bonus scene is of a haunted mansion, and uses dark, purple light for a spooky, unnatural feel, with low ambient lighting and a flickering effect as if the lights are turning on and off. The light is above and slightly off to the side as if it is a lamp on the side of a room.

## Scene

The starter scene contains:

- Two colored cubes
- A smaller sphere
- A pyramid
- A ground plane
- Ambient lighting
- Directional lighting
- A fixed elevated camera view

The scene is intentionally static. Objects do not animate and the light direction remains fixed.

## Files

- `weekly4.html` contains the canvas, embedded vertex and fragment shaders, and the JavaScript include.
- `weekly4.js` creates the meshes, camera, lighting, and draw calls.

## Run

Open `weekly4.html` in a browser with WebGL enabled. For a local development server, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/weekly4.html](http://localhost:8000/weekly4.html).

## Requirements

- A modern browser with WebGL support
- Python 3, only if using the local development server

# Reflection Questions
### Which scene was the easiest to create?
The easiest to create in my opinion was the moonlit one. Moonlight is distinct enough that I was confident in how it should look, and a color change and lower ambient light was all that was really needed to make it instantly feel like a moonlit scene.
### Which scene looked the most realistic?
Also the moonlit one, since it was easiest for me to get the color right. 
### How did ambient light affect the mood of each scene?
The darker the ambient light, the more distinctive the color scheme and the moodier it is. For example, the moonlit one and campfire one are the most recognizable as what they're supposed to be and feel more somber, while the other two feel more generic and have a brighter mood.
### How did light direction affect visibility?
The further from the center the light was, the more that all of the objects were visible. The campfire one did not light all of the objects, while the above-head light positions did.
### Which color produced the strongest visual effect?
Once again, I think that the moonlight one did. The blue color is very distinctive. 
### Why do game developers spend so much time adjusting lighting?
Small tweaks in the direction or color of a light can vastly change the mood of a scene and helps to communicate to the player what sort of environment they're supposed to be in. 
### If you were making a horror game, what lighting would you use and why?
The final haunted mansion one that I created, as it feels very spooky with the unnatural color of the light and the flickering effect creates tension.