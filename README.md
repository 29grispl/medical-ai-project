# Medical AI Project

I made some sort of medical AI that can detect tuberculosis in chest x-rays with a 79% accuracy on both TB+ and TB-, a 100% accuracy on TB- and a 58% accuracy on TB+. I didn't even get top 5, so if anyone wants to expand on this, here.

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
