Witam w README
Instrukcja instalacji:
---------------------------------------------------------------------
1.
Przez git bash wejść do folderu pobranego z tego repo (cw_praca_z_kodem)
cd ../../cw_praca_z_kodem
I zainstalować wirtualne środowisko python
python -m venv <nazwa>

source <nazwa>/Scripts/activate

by wyłączyć środowisko: deactivate
----------------------------------------------------------------------
2.
W bashu wpisujemy:
make install
make flask

w cmd wpisujemy
curl http://127.0.0.1:5000/
curl http://127.0.0.1:5000/hello/
curl http://127.0.0.1:5000/hello/<name>
-----------------------------------------------------------------------
3.
Aby zmienić imię należyć zmienić funkcje hello w pliku app.py
