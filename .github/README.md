# RealTimeMemoryAllocationSimulator

A small, browser-based Real Time Memory Allocation Simulator. The repository currently contains a single HTML file that runs the simulator in the browser.

## Contents

- `index.html` — main entry point. Open this file in a browser to run the simulator.

## Quick start

Option 1 — open directly

1. Double-click `index.html` or open it from your browser (File -> Open File).

Option 2 — serve via a local HTTP server (recommended for best browser behavior)

Open PowerShell in the project folder and run one of the following:

```powershell
# If you have Python 3 installed
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

The simulator should load and run in your browser. If the UI requires interaction, use the controls on screen.

## Development notes

- This is a static frontend app. No build step is required—changes to `index.html` are picked up on refresh.
- If you add assets (CSS/JS), keep them next to `index.html` or update paths accordingly.

## Contributing

If you'd like to contribute:

1. Fork the repository.
2. Create a branch for your feature or bugfix.
3. Open a pull request with a clear description of changes.

## License

No license file is provided in this repository. If you want this project to be open source, add a `LICENSE` file (e.g., MIT) and update this section.

## Contact

For questions or help, open an issue in this repository.

---
