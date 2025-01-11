Download in zip file.
Unzip it.
create environment "python -m venv env"
install all libraries "pip install -r requirements.txt"
first make ".env" file in root directory and include your api key in it like this "OPENAI_API_KEY = sk---*****abcd"
put your dataset in "files/pdf"
run the app "uvicorn main:app"
