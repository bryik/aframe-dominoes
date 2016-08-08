# A-Frame Dominoes

<p align="center">
  <img src="http://i.imgur.com/myHEg8E.gif"/>
</p>

Playable with **HTC Vive**.

This repository contains a small demonstration of A-Frame with Vive controllers and physics powered by [A-Frame Extras](https://github.com/donmccurdy/aframe-extras).

### Controls

Press (and hold) the **trigger** to pickup a domino, release the trigger to drop.

Push the **trackpad** to spawn a domino. Release the trackpad to drop.

Press the **menu** button to remove dominoes from the table.

Pressing the **grip** buttons will cause a stick to materialize at the end of your controller. Useful for setting off dominoes at a distance. Press the grips again to make it disappear.

See [this video](https://www.youtube.com/watch?v=gU-P-56kAnI) for a demonstration.

### Bugs and Instability

The physics system is a bit unstable. Weird things may happen! The preset dominoes sometimes explode or topple over when I load the page.

### Local Development

To serve the site from a simple Node development server:

    npm start

Then launch the site from your favorite browser:

[__http://localhost:3000/__](http://localhost:3000/)

If you wish to serve the site from a different port:

    PORT=8000 npm start


## License

This program is free software and is distributed under an [MIT License](LICENSE).
