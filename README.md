# Weight Training

An interactive browser-based introduction to model weights, built by ProjectionHeart. The lessons use SD-Turbo and the LiveGrid projection pipeline as a concrete example.

## Lessons

1. Follow a prompt through tokenization, the text encoder, U-Net, VAE decoder, and projection output.
2. Experiment with inputs and weights in a tiny neural network, then take a toy learning step.
3. Compare tensor storage across precision formats and separately loaded model copies.
4. Check your understanding with questions and feedback.

The small network is an educational simulation, not SD-Turbo inference. No model weights are loaded or changed. No accounts, credentials, API calls, analytics, or GPU are needed.

## Run locally

Open index.html in a browser, or serve this folder with any static web server. There is no build step or dependency installation.

## Publish

Use GitHub Pages with the main branch and root folder. The intended site is https://projectionheart.github.io/weight-training/.

## Files and sources

- index.html: lesson content and accessible controls
- learn.css: responsive styles
- learn.js: simulations, storage calculator, and quiz
- MODEL-MANIFEST.json: source model revision and verified download checksums

The storage figures describe the fp16 SD-Turbo files packaged for [LiveGrid](https://github.com/projectionheart/livegrid-generative-ai). The hypothetical precision comparisons exclude runtime memory and quantization overhead. The 100-square output shares one model stream.

See the [SD-Turbo model card](https://huggingface.co/stabilityai/sd-turbo) and [model guide](https://github.com/projectionheart/livegrid-generative-ai/blob/main/Model-Weights-README.md). Model downloads and their license remain in the original LiveGrid repository; this repository contains the learning tool only.

Powered by Stability AI.
