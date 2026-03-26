Filer i prosjektet:
server.py = Programmet som styrer dataene.
client.py = Programmet jeg bruker for å skrive inn oppgaver.
todos.json = Her lagres alle listene mine.

For å starte den på mac må du gjøre følgende:

Installer nødvendige verktøy ved å skrive "pip3 install flask requests" i terminalen.

Så for å starte serveren må du skrive "python3 server.py" i terminalen.

Etter dette må du starte klienten i et nytt terminalvindu (cmd + N).
Så skriver du følgende i terminalen:
python3 client.py

I client.py kan du velge følgende:
1 - for å se alle lister.
2 - for å se innholdet i en liste.
3 - for å lage en ny liste.



Programmet bruker flask og requests.