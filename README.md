# CNN Lab — Digit & Alphabet Recognition

A lightweight, browser-based educational demo for experimenting with handwritten digit and alphabet recognition using a simple CNN-style pipeline. The project is made of standalone HTML files and can be run locally without a server.

## 📁 Project Files

| File | Description |
|---|---|
| `Index.html` | Free-draw digit recognition demo. |
| `Alphabet.html` | Alphabet recognition demo for letters **A–Z**, with formula and calculation views. |
| `Numbers.html` | Digit recognition demo for numbers **0–9**, with CNN formula and numeric calculation views. |

## ✨ Features

- Draw letters or digits directly on a canvas — no input grid.
- Display prediction scores for supported classes.
- Educational calculation views for parts of the model pipeline, such as convolution, ReLU, pooling, dense-layer scores, and softmax.
- Training/demo controls, depending on the page.
- Local browser usage; no server is required for basic use.

## 🚀 Getting Started

### Option 1: Run locally

1. Download or clone this repository.
2. Open `Index.html`, `Alphabet.html`, or `Numbers.html` in a modern web browser.
3. Wait for any initial model setup or pretraining to finish.
4. Draw a digit or letter on the canvas.
5. Click the page's prediction/recognition button to see the result.

### Option 2: Use GitHub Pages

1. Upload all three HTML files and this `README.md` to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch (usually `main`) and the `/ (root)` folder, then save.
5. Once GitHub Pages publishes the site, open the URL it provides.

If you want the repository homepage to open the digit demo automatically, rename `Index.html` to `index.html` (lowercase) or create a lowercase `index.html` entry point. GitHub Pages expects the default homepage filename to be lowercase `index.html` in the published directory.

## 🧠 Model Notes & Limitations

- The demo uses locally generated/synthetic training examples; it is **not** a pretrained production model and does not imply use of the MNIST dataset.
- Prediction percentages represent the model's confidence scores, not a guarantee that a prediction is correct.
- Handwriting recognition accuracy may vary. Results depend on the drawing style and the model's training.
- The calculation panels are intended for learning and visualization. The convolution filters may be fixed while classification-layer weights are trained, depending on the page implementation.
- Initial training can take a short time, especially on slower devices.

## 🧰 Requirements

- A modern browser with JavaScript enabled.
- No package installation or build tools are required for the standalone HTML demos.

## 📦 Repository Structure

```text
.
├── README.md
├── Index.html
├── Alphabet.html
└── Numbers.html
```

## 🤝 Contributing

Suggestions and improvements are welcome. You can open an issue or submit a pull request with a clear description of the change.

## 📄 License

No license is specified yet. Add a `LICENSE` file before presenting the project as open source under a particular license.
