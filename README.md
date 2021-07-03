Create a new Environment:

```bash
conda create -n DelloiteCaseStudy
```

Activate Environment:

```bash
conda activate DelloiteCaseStudy
```

Install requirement file:

```bash
pip install -r requirements.txt
```

Initialize git:

```bash
git init
````


Initialize dvc:

```bash
dvc init
```

Tracking data:
```bash
dvc add data_given/CaseStudy_20190517.xslx
```

First Commit:

```bash
git add .
git commit -m "First Commit"
git remote add origin https://githib.com/ssumitk14/Delloite-Case-Stdy.git
git branch -M main
git push origin main
```


