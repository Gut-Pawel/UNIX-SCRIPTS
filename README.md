# check-if-synchronized
Bash script that checks if the files in the specified directory are synchronized.

PL:
Skrypt BASH który sprawdza czy pliki na wskazanym zdalnym serwerze i katalogu istnieją oraz porównuje ich wielkość. 
Następnie generuje plik CSV do którego zapisuje wynik dla każdego pliku znajdującego się w wskazanym katalogu.

Skrypt wysyła zapytania za pomocą SSH więc należy wygenerować klucz RSA.

Zmienne w kodzie które należy uzupełnić:
targetHost=user@hostname
mainDirPath=<ścieżka katalogu>
raportCSV=<ścieżka do pliku CSV>/raport_YYYYMMDD_HHmmSS.csv

