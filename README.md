Custom layers for pydeck
========================

This repo is an example of how to create a custom deck.gl layer for use in pydeck.

To get started with this example repo, install the dependencies:

```bash
yarn
python3 -m venv env
. env/bin/activate
pip install -r pydeck_example/requirements.txt
```

Then execute the following to a pydeck script and serve the JavaScript bundle:

```bash
python pydeck_example/labeled_geojson_layer.py
webpack serve --progress
```

Navigate to http://localhost:8080/custom_layer.html in your browser, which should render the visualization.

You can deploy your project to NPM and host the your bundle on unpkg, which you can see in the
[custom layer example in the pydeck docs](https://pydeck.gl/gallery/custom_layer.html).


### Nebula
Trying to import nebula using this example
https://github.com/hubmapconsortium/vitessce/blob/3ac8d385a659afbbe594d754ed0883f1a56d8813/src/layers/SelectionLayer.js#L11

and this example

https://codesandbox.io/s/deckgl-and-nebulagl-editablegeojsonlayer-no-react-forked-7fcst?file=/app.js:86-144

Following these instructions to get rid of error

https://github.com/uber/nebula.gl/issues/485