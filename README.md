# PhishShield Starter (with CI + Tests + Coverage)

Minimal project so you can demonstrate CI coverage for your QMP.

## Run locally
```bash
pip install -r requirements-dev.txt
pytest --cov=app --cov-report=term-missing
pytest --cov=app --cov-report=html  # then open htmlcov/index.html
```

## CI on GitHub
1. Create a new GitHub repo (empty).
2. Copy this whole folder into your repo and commit:
   ```
   git add .
   git commit -m "PhishShield starter with CI"
   git branch -M main
   git remote add origin https://github.com/<you>/phishshield-starter.git
   git push -u origin main
   ```
3. Open the **Actions** tab to see the CI run, coverage %, and coverage.xml artifact.

Generated: 2025-10-26
