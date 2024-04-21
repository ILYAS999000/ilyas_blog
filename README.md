GERMAN

Nach Download von der Blog-APP

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




ENGLISH 

After downloading from the blog APP

-create virtual environment

-requirements.txt Install packages

-Set PostgreSQL access in settings.py and activate PostgreSQL database

-migrate everything with the command python manage.py migrate

-Use the command python manage.py createsuperuser to create a SuperUser for the admin page

-runserver via localhost

After configuration

-log in to the Django admin page via localhost -----http://127.0.0.1:8000/admin/----- with the created SuperUser -now you can create posts, comment on created posts, group or Assign user rights and manage everything else!

-on your own homepage via localhost -----http://127.0.0.1:8000/ilyas_blog/------ you can then see the view of the blog page with all entries and search for blog entries, latest or most commented blog entries View and comment on blog entries, subscribe to the RSS feed, list by tags, see the publication date and publisher of each post and these pages are SEO friendly.

!!!!Very important, you can only add blog entries as a SuperUser via the admin page!!!!

I also tried to explain all the steps in the code in detail, it may be a bit too much, but this was very important to me so that third parties could understand it. If you have any questions, you can contact me at hans-50999@web.de Have fun with it ;-)
