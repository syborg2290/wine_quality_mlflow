conda create -n wineQ python=3.7 -y -> CMD(Not the PowerShell)
conda activate wineQ
conda activate wineQ for activate conda environment(wineQ is name of environment)

pip freeze > requirements.txt -> To write the installed libs
pip install -r requirements.txt -> Install the all the libs from requirements.txt

https://c17hawke.github.io/wafer_mlops_docs/stage1_init_setup/ -> (Doc Url)


create env

conda create -n wineQ python=3.7 -y
activate env

conda activate wineQ
created a req file

install the req

pip install -r requirements.txt
download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"
oneliner updates for readme

git add . && git commit -m "update Readme.md"
git remote add origin https://github.com/c17hawke/simple-dvc-demo.git
git branch -M main
git push origin main
tox command -

tox
for rebuilding -

tox -r
pytest command

pytest -v
setup commands -

pip install -e .
build your own package commands-

python setup.py sdist bdist_wheel



