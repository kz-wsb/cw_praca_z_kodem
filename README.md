Tworzę wirtualne środowisko Pythona (o nazwie python-env):
python3 -m venv python-env

i aktywuję je:
python-env\Scripts\activate.bat

instaluję bibliotekę pip:
pip install –r requirements.txt

oraz narzędzie pylint:
pip install pylint

aplikację flask uruchamiam komendą:
flask run