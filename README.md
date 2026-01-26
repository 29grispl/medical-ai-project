# Medical AI Project

TB detection from X-ray images.

## Quick Setup

```bash
git clone https://github.com/29grispl/medical-ai-project.git
cd medical-ai-project
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
```

## Why requirements.txt and not venv folder?

Virtual environments are tied to your specific computer. If you copy the `venv` folder to another machine, it breaks. 

`requirements.txt` is just a recipe - pip reads it and builds a fresh venv on your computer. Works everywhere.

## Project Structure

```
data/
  ├── tb_positive/
  └── tb_negative/
models/
  └── centroids.npz
```

Done!

