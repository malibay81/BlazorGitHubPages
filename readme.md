### Welcome to my first hosted wep app on github static pages !

Zum Publishen wird folgendes Befehl benötigt :

`dotnet publish -c Release -o release`

Dieses Befehl erzeugt ersmal das Projekt in den release Ordner.

Dieser sollte jetzt zunächst im übergeordneten Ordner zwischengespeichert werden.

Anschließend wechseln wir mit dem Befehl den Branch :

`git switch gh-pages`

Der Inhalt von release/wwwroot wird jetzt in den main ordner vom aktuellen branch kopiert und auf githun gepusht.

Alles was hier im branch committed und gepusht/sync wird landet auf github und wird automatisch compiliert und übernommen.

Hierfür wurde bereits eine Repository angelegt, s. auf github.
