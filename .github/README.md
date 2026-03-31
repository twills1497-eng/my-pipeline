# My CI/CD Pipeline Project
 
A fully automated CI/CD pipeline built from scratch.
 
## Live Demo
https://my-pipeline-i48m.onrender.com/
 
## Tech Stack
- Python / Flask — web application
- Docker — containerization
- GitHub Actions — automated testing on every push
- Render — cloud deployment
 
## How it works
1. Code is pushed to GitHub
2. GitHub Actions automatically runs pytest tests
3. If tests pass, Render auto-deploys the new version
 
## Run locally
git clone https://github.com/twills1497-eng/my-pipeline
pip install -r requirements.txt
python app.py