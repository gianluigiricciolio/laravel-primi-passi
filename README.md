nome repo: laravel-primi-passi

Oggi iniziamo a muovere i primi passi con questo fantastico framework che è Laravel!
Per prima cosa, creiamo un nuovo progetto Laravel, utilizzando questo comando:

composer create-project laravel/laravel:^10.0 laravel-primi-pass

Al termine dell'installazione, entriamo nella cartella del progetto

cd laravel-primi-passi

e avviamo l'artisan serve con uno di questi due comandi:

php artisan serve   oppure
php -S localhost:8000 -t public

A questo punto, iniziamo a prendere confidenza con le rotte e le views: cancelliamo la view welcome.blade.php e creiamo una nostra homepage.
Facciamo quindi sì che la rotta / visualizzi home.blade.php
Inizialmente stampiamo un Hello World