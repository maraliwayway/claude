# sidekick

## setup

cd to backend
1. pip install -r requirements.txt

create a venv
2. python3 -m venv venv 
3. source venv/bin/activate

installation
4. pip3 install pandas
4. uvicorn main:app --reload
4. pip install ollama

5. ollama pull gemma:2b


use older version of python 
1. brew install pyenv
2. pyenv install 3.11.9  # or 3.10.14
3. pyenv local 3.11.9

create a new venv
4. python3 -m venv venv
5. source venv/bin/activate

install dependencies 
6. pip install --upgrade pip
7. pip install -r requirements.txt
8. pip install pandas

run uvicorn
9. pip install --upgrade pip
10. pip install -r requirements.txt
11. pip install pandas

get the thing running 
12. python -m uvicorn main:app --reload