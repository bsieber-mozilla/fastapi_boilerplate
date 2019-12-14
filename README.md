Prereqs:
pipenv installed

Don't have pipenv?
brew install pipenv

git clone https://github.com/bsieber-mozilla/fastapi_boilerplate.git
cd fastapi_boilerplate/
pipenv install
pipenv shell
(shell) uvicorn main:app --reload

View Api docs while running:
http://localhost:8000/docs
http://localhost:8000/redoc

Run api:
http://localhost:8000/items/5?q=somequery
