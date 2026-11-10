# InkTeX

An independent student research/development project for converting images of
handwritten mathematical expressions into LaTeX. InkTeX succeeds BUDDHI v0.1.0
and starts with a fresh codebase.

Currently, this repository contains only the initial scaffold. No pretrained
checkpoint has been selected, and image recognition is not implemented or verified.
The next step is to select a pretrained image-to-LaTeX Transformer after checking
its availability, suitability for handwritten mathematics, dependencies, and license.

Install dependencies with Python 3:

```sh
python3 -m pip install -r requirements.txt
```

There are no third-party dependencies yet. To check the current status:

```sh
python3 inference.py
```

The script exits with a message that model selection is pending. A runnable baseline
will accept an image of a single expression and print predicted LaTeX once a
checkpoint is selected and integrated. Training and evaluation are not implemented.
