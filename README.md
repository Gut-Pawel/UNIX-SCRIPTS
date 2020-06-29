# CSV-GEN_checkIfSynchronized
Bash script that checks if the files in the specified directory are synchronized.

PL:

Skrypt CSV-GEN_checkIfSynchronized:
-Raport generowany jest w formacie CSV
-Aby wskazać serwer zdalny należy uzupełnić zmienną "targetHost" w kodzie [np. targetHost=root@mojserwer123].
-Aby ustalić nazwę oraz ścieżkę generowanego reportu należy uzupełnić zmienną "raportCSV" w kodzie [np. /data/raports/raport_YYYYMMDD_HHmmSS.csv].
-Skrypt wysyła zapytania za pomocą SSH więc należy wygenerować prywatny klucz RSA na hoście zdalnym oraz klucz publiczny na hoście zdalnym.

