# Impulse Response Application in Python

This project demonstrates how to apply an impulse response (IR) to an audio file using Python and a Jupyter Notebook.

## Setup Instructions

1. **Clone the repo and navigate to the project folder:**

```bash
git clone <your-repo-url>
cd apply_ir_project
````

2. **Create and activate a virtual environment:**

```bash
# Create
python3 -m venv venv

# Activate
# macOS/Linux:
source venv/bin/activate

# Windows:
venv\Scripts\activate
```

3. **Install requirements:**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter in VS Code:**

Open the `apply_ir.ipynb` file in VS Code and select the interpreter from the virtual environment.

---

## Dependencies

* `numpy`
* `scipy`
* `librosa`
* `soundfile`
* `matplotlib` (for visualizing waveforms)

---

## Notes

* Put your impulse response in `audio/impulse_response.wav`
* Put your dry audio input in `audio/dry_audio.wav`

### ✅ Folder Structure

```
apply_ir_project/
│
├── README.md
├── requirements.txt
├── apply_ir.ipynb
└── audio/
    ├── impulse_response.wav
    └── dry_audio.wav
```