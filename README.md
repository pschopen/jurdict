# Jurdict
Jurdict ist ein kostenloses Sprachpaket zur Verwendung in Microsoft Word und LibreOffice. Es enthält bisher die wichtigsten juristischen Abkürzungen, lateinischen Fachbegriffe und die Namen der bekanntesten Rechtswissenschaftler. Es richtet sich an Anwälte, Wissenschaftler, Studenten und andere Juristen.

# Installation
## Microsoft Word 
Die im Paket enthaltene .dic-Datei kann einfach in Word über <code>Einstellungen > Rechtschreibung und Grammatik > Wörterbücher > Hinzufügen</code> (MAC) und <code>Datei > Optionen > Dokumentenprüfung > Benutzerwörterbücher > Hinzufügen</code> (WINDOWS) eingefügt werden. Bitte beachten Sie, dass Word immer im angegebenen Ordner nach der Datei suchen wird. Sie dürfen die Datei von dort also nicht löschen oder verschieben.

Unter Umständen ist es in einigen Versionen von Word erforderlich, im Datei-Manager das Anzeigen von allen Dateien zu erlauben, um die jurdict-sprachpaket.dic auswählen zu können.

## LibreOffice
Zur Verwendung in LibreOffice muss am Anfang der Wörterbuch-Datei <code>jurdict-sprachpaket.dic</code> die in Zeile 1 stehende Word-Sprachkennung <code>#LID 1031</code> entfernt und durch den 4-zeiligen Vorspann für LibreOffice-Benutzerwörterbücher ersetzt werden:  
<code>OOoUserDict1  
lang: <none>  
type: positive   
\---</code>  

Die derart modifizierte Datei kopiert man dann in das Standardverzeichnis für Benutzerwörterbücher: <code>C:\Program Files\LibreOffice\share\wordbook\\</code> (Windows) bzw. <code>/usr/lib/libreoffice/share/wordbook/</code> (Linux). Beim nächsten Start von LibreOffice kann das benutzerdefinierte Wörterbuch dann in <code>Extras > Optionen > Sprachen und Gebietsschmata > Linguistik</code> aktiviert werden.
# Mitmachen
Wenn Ihnen einzelne Worte fehlen oder Sie die Ergänzung einer ganzen Wortsammlung vorschlagen möchten, können Sie dies über den Reiter "Issues" im oberen Bildbereich auf Github erledigen.

# Rechtliches
## Lizenz
Jurdict steht unter der Creative Commons Lizenz "CC BY-SA 3.0". Sie können das Produkt in jedweder Form für sich kommerziell nutzen und es unter den Bedingungen der CC-Lizenz auch teilen. Die Bedingungen der CC-Lizenz sind Namensnennung und gleiche Bedingungen. Die Vermarktung als kommerzielles Produkt ist damit ausgeschlossen. Weitere Informationen gibt es hier: https://creativecommons.org/licenses/by-sa/3.0/deed.de

## Credits
Die juristischen Abkürzungen, Fachbegriffe und Namen sind der deutschsprachigen Wikipedia entnommen und wurden im Anschluss daran erweitert. www.wikipedia.org

Jurdict umfasst seit Version 1.1 in Ergänzung von Word mit Zustimmung von Verfasser und Verlag alle halbfett gesetzten Stichwörter von
Köbler, Gerhard, Juristisches Wörterbuch, 18. Aufl., (Verlag) Vahlen, München 2022, ca. 600 S., das durch 8700 Lemmata systematisch den gesamten aktuellen Rechtsgrundwortschatz für Studium und Ausbildung in Deutschland erfasst, in dem anschließenden Text mit vielen Beispielen knapp und klar erläutert und vertieft sowie in fast weiteren 4500 Absätzen um wichtige weiterführende Literaturhinweise bereichert.

&copy; Philip Schopen
