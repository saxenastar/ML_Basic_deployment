# ML_Basic_deployment
ML project deployment with the helloword dataset i.e. iris flower dataset.

- Anaconda: https://www.anaconda.com/
- Vs code: https://code.visualstudio.com/download
- Git: https://git-scm.com/



## git commands
``` bash
git clone git_repo_url

git add .

git commit -m "message about the update "

git push origin main
```

## how to run ?
``` bash
conda create -n ml_basic python=3.8 -y

conda activate ml_basic

python template.py 

pip install -r requirements.txt
(-e . is used in requirements.txt file for to setup own python package but 
this also require setup.py file so first setup )

pip list
```