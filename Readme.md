MLOPs Introduction 

create the conda env by using below commands 
```bash
conda create - n <envname> python=3.8 -y
conda activate <envname>
pip install -r requirements.txt
git init
dvc init
git add .
git commit -m "First commit "
git remote add origin <repo link.git>
git branch -M main
git push origin main
```