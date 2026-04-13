MinTodoApp

Filer i prosjektet:
server.py = Programmet som styrer dataene.
client.py = Programmet jeg bruker for å skrive inn oppgaver.
todos.json = Her lagres alle listene mine.

For å starte den på mac må du gjøre følgende:

Installer verktøyene som trengs:
Skriv "pip3 install flask requests" i terminalen.

Start serveren:
Skriv "python3 server.py" i terminalen.

Start klienten:
Åpne et nytt terminalvindu (cmd + N) og skriv:
"python3 client.py"

I klienten kan du velge følgende:
1 - Se alle lister (ID og tittel).
2 - Se innholdet i en liste (her ser du tittel, tekstnotat og oppgaver).
3 - Lage en ny liste (her skriver man inn tittel, et tekstnotat og oppgavene).

Programmet bruker flask og requests.