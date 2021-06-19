create env
```bash
conda create -n wineq python=3.7 -y
```

activate 
conda activate wineq

install the requirements
'''bash
pip install -r requirements.txt

download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

git init 

dvc  init 

dvc add data_given/winequality.csv

git add . 

git commit -m "first commit"

git remote add origin https://github.com/ninad555/simple-dvc-demo.git

git branch -M main

git push -u origin main
 
+ git init 

+ git branch -M main

+ git commit -m "first commit"

+ git push -u origin main 

tox command -
```bash
tox 
```

for rebuilding -
```bash
tox -r
```

pytest command - 
```bash
pytest -v 
```

setup commands - 
```bash 
pip install -e.
```

build your own package commands-
```bash
pyton setup.py sdist bdist_wheel
```
