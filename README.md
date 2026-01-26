# Medical AI Project

This is a science fair project where I tried building an AI model that uses cosine similarity to recognize tuberculosis in lung x-rays. The goal was to learn how image recognition works in practice, see how accurate this approach could be, and understand what went wrong and how it could be improved.

## Quick Setup

```bash
git clone https://github.com/29grispl/medical-ai-project.git
cd medical-ai-project
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
```

## Project Structure

```
data/
  ├── tb_positive/
  └── tb_negative/
models/
  └── centroids.npz
```
