# Medical AI Project

A medical AI project for tuberculosis detection from X-ray images.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/29grispl/medical-ai-project.git
cd medical-ai-project
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**On macOS/Linux:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
venv\Scripts\activate
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

## Understanding the Virtual Environment

**What is a venv?**
A virtual environment (`venv`) is a self-contained Python folder with all your project's dependencies installed.

**Why don't we include the venv folder in the repository?**
- Virtual environments are machine-specific and break when moved to another computer
- Paths are hardcoded for the original system
- Different operating systems need different compiled packages

**How does requirements.txt solve this?**
- `requirements.txt` is just a text file listing all package names and versions
- When you run `pip install -r requirements.txt`, it installs all those packages into your fresh venv
- This creates a working environment tailored to your computer

**Analogy:**
- Including venv = shipping a pre-made sandwich that will go stale
- Including requirements.txt = shipping a recipe so you can make a fresh sandwich

## Project Structure

```
data/
  ├── tb_positive/     # X-ray images of TB-positive cases
  └── tb_negative/     # X-ray images of TB-negative cases
models/
  └── centroids.npz    # Pre-trained model centroids
```

## Running the Project

After activating your virtual environment, you can run your project files:
```bash
python your_script.py
```

## Dependencies

Key packages included:
- pillow (image processing)
- numpy (numerical computing)
- And 98+ other packages (see requirements.txt for full list)

