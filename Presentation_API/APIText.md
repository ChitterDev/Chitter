# Chitter API
Die API, die Daten von der Datenbank holt und verarbeitet wird von mir in Typescript mithilfe von NODE.js programmiert.
An alle die es nicht wissen mit Node.js lässt sich Javasctipt Code Server seitig ausführen.
Hinter Node.js verbirgt sich die JavaScript-Laufzeitumgebung "V8" die auch in Google Chrome verwendet wird.
Javascript ist eine Eventgesteuerte Sprache.
Dies hat im Server seitigen Betrieb den Vorteil, dass pro bestehender Verbindung weniger Arbeitsspeicher verbraucht wird als bei vergleichbaren Anwendungen die für jede Verbindung einen eigenen Thread starten.
Und da unser Rest Service auf JSON basiert ist Node.js eine sehr gute wahl,
da sich JSON in JavaScript nativ verarbeiten lässt.
Außerdem ist Node.js mit Express.js perfekt geeignet um HTTP basierte Webanwendungen zu entwickeln und lässt sich sehr gut skalieren.
Mit dem Node Package Manager kurz npm lassen sich sehr leicht sehr umfangreiche Module hinzufügen. Mit dem NPM lassen sich mittlerweile über 400.000 Pakete hinzufügen.
Eines dieser Packages ist Express.js und dient als Web-Framework.

Wieso verwenden wir Typescript?
Typescript hat einige vorteile wie statische Typisierung.
Statisch Typisierte Sprachen vermindern die Fehler und IDEs können dir bessere vorschläge bieten.
Natürlich muss man ein bisschen mehr tippen und typen sind optional in Typescript.
Doch wenn man sich daran hält vereinfacht es das zusammenarbeiten enorm.
Außerdem wieso sollte man es nicht verwenden jeder JavaScript code ist gültiger Typescript Code.
Somit ist das umsteigen auf Typescript auch keine riesen Hürde.

Unsere Errors werden mithilfe von Sentry geloggt.
Sentry ist eine moderne error logging und Aggregations platform.
Das Sentry Package ist eigentlich nur ein WebServer mit einem WebInterface.
Für Node.js und viele andere Sprachen gibt es auch eine sehr gute SDK mit der man die Errors sehr leicht loggen kann.

WEBINTERFACE HERZEIGEN.

VLLT über JWT reden

# Chitter Website
Unsere Website wird mithilfe des JavaScript Frameworks Angular geschrieben.
