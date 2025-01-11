Download in zip file.<br />
Unzip it.<br />
create environment "python -m venv env"<br />
install all libraries "pip install -r requirements.txt"<br />
first make ".env" file in root directory and include your api key in it like this "OPENAI_API_KEY = sk---*****abcd"<br />
put your dataset in "files/pdf"<br />
run the app "uvicorn main:app"<br />
