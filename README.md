# Lista-zakupow

Aby uruchomić stronę należy pobrać repozytorium i otworzyć je w PyCharm-ie. 
Konfiguracje powinny ustawić się automatycznie, a strona będzie gotowa do otworzenia na porcie 8000.

Strona administratora dostępna pod adresem:  
http://127.0.0.1:8000/admin/  
Dane logowania:  
login: admin  
hasło: admin

Strona główna z listą dostępna pod adresem:  
http://127.0.0.1:8000/shoping_list/  


Wymagania  
Python 3.9.X  
Django 3.1.7 lub nowszy  


## Workflow  

Każda zmiana w repozytorium przebiega w określony sposób:
* Tworzymy taska w Projects.
* Tworzymy Issue w oparciu o tegi taska.
* Tworzymy Branch odpowiadający danemu issue.
* Wszystkie zmiany commitujemy do stworzonego brancha dla danego issue, rozpoczynając komentarz od Shopping_list i po dwukropku opis czego dotyczy zmiana.
* Gdy kod jest gotowy do oceny, otwieramy merge request.
* W merge request dodawane są komentarze odnośnie kodu, po poprawieniu kod jest ponownie oceniany aż do momentu gdy wszystkie dyskusje są rozwiązane.
* Po zaakceptowaniu merge requesta, nasz branch wchodzi do maina.

