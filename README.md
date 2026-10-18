# Product Pattern Preview

Browser-based 3D product pattern preview with eight example styles and local image upload. Includes scale, horizontal/vertical position, 90-degree rotation and reset controls.

Images are processed locally in the visitor’s browser. No uploaded images are sent to a server.

## Deployment

The complete static website is in `site.zip`. Extract with:

```sh
python3 -m zipfile -e site.zip .
```

Publish directory: `dist`.

Product designs and model assets are provided for preview; no redistribution license is granted. Three.js retains its bundled MIT license at `dist/vendor/LICENSE-three.txt`.
