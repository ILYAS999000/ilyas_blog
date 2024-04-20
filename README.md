Nach Download
-virtuelle Umgebung erstellen
-requirements.txt Packete installieren
-PostgreSQL-Zugang in settings.py einstellen sowie PostgreSQL Datenbank aktivieren
-mit Befehl python manage.py migrate alles migrieren
-mit Befehl python manage.py createsuperuser einen SuperUser erstellen für die Admin-Seite
-runserver über localhost

Nach Konfiguration
-auf der Django-Admin-Seite über localhost -----http://127.0.0.1:8000/admin/----- mit erstellten SuperUser anmelden
					-jetzt kann man Posts erstellen, erstellte Posts kommentieren, Gruppen- oder Userrechte					vergeben, und alles andere verwalten!
-auf der eigenen Homepage über localhost -----http://127.0.0.1:8000/ilyas_blog/------ kann man dann die Ansicht der Blogseite sehen mit allen Einträgen und nach Blogeinträge suchen, letzte oder meistkommentierte Blogeinträge anschauen und Blogeinträge kommentieren, RSS-Feed abonnieren, nach Tags listen, Veröffentlichungsdatum und Veröffentlicher von jedem Posts sehen und diese Seiten sind SEO freundlich eingerichtet.

!!!!Ganz wichtig, man kann nur Blogeinträge als SuperUser hinzufügen über die Admin-Seite!!!!

Ich habe auch versucht alle Schritte im Code detailreich zu erklären, es kann auch etwas zu viel sein, aber für die Verständlichkeit Dritter war das mir sehr wichtig. Falls Fragen sind dann können sie mich kontaktieren unter hans-50999@web.de
Viel Spaß damit
;-)
