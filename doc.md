python -m venv .venv
source .venv/Scripts/activate

pip install -r requirements.txt

git config --global user.name "KostiaUek"
git config --global user.email "146982394+KostiaUek@users.noreply.github.com"

pip freeze > requirements.txt