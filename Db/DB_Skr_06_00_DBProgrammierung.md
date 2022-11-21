# 6 Datenbankprogrammierung

SQL ist als reine Zugriffs- und Verwaltungssprache entworfen worden. Anfänglich gab es in SQL keine Kontroll-, Schleifen- oder Verzweigungsanweisungen. Sie beschränkt sich auf die Beschreibung und den Zugriff auf die Datenbank.

In modernen Programmen wird eine komfortable Oberfläche erwartet. Damit ergibt sich der Zwang sich an Programmierumgebungen außerhalb der Datenbank zu binden. Typische Anwendungsfälle:

- Desktop-Anwendung: hier sind Java-Anwendungen sehr verbreitet. Andererseits bietet Microsoft für die reine Windows-Welt mit Visual-Studio ein sehr umfassendes Entwicklungswerkzeug.
- Internet-Anwendungen: sie haben den großen Vorteil, dass sie von allen Rechnern, Smartphones oder Tablets ohne Aufwand verwendet werden können. Hier spielen JSP (Oracles Java Server Pages), ASP.NET (Microsoft), [[DB_Skr_06_02_Nodejs|Node.js]] und [[DB_Skr_06_01_PHP|PHP]] (Open Source)