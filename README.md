
Create environment

```bash
conda create -n wineq python=3.7 -y
```
Activate environment

```bash
conda activate wineq
```
Created a requirements file

Install the requirements
```bash
pip install -r requirements.txt
```
Download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
```bash
git init
dvc init 
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"
```
Online updates for readme

```bash
git add . && git commit -m "update Readme.md"
git remote add origin https://github.com/trehansalil/simple-dvc-demo.git
git branch -M main
git push origin main
```