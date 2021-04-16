# Caesa-Verschluessung

Aufgabenstellung
In [Leib] wird der Doppelwürfel als ein für Spione optimales Hand-Verfahren zur Verschlüsselung
beschrieben:
"Geheimer Bestandteil des Verfahrens ist ein Losungswort (im Beispiel "Schwarzwald"). Man
sortiert die Buchstaben des Losungswortes nach dem Alphabet, nummeriert sie durch und schreibt
unter jeden Buchstaben des Losungswortes seine so ermittelte Nummer. Das ergibt die sogenannte
Zahlenlosung; es handelt sich um eine Permutation der Zahlen von 1 bis n, wobei n die Länge des
Losungswortes ist." Im Beispiel lautet die Zahlenlosung (8 3 5 9 1 7 11 10 2 6 4), in Ihrer Lösung
nummerieren Sie die Spalten von 0 bis n-1, nehmen also die Permutation (7 2 4 8 0 6 10 9 1 5 3).
"Nach dieser Vorbereitung gewinnt man den Geheimtext, indem man unter die Losung zeilenweise
den Klartext einträgt und spaltenweise in der Reihenfolge der Losungsnummern wieder ausliest.
Der Empfänger des Geheimtextes schreibt zunächst die (Zahlen-)Losung nieder und zeichnet sich
einen Würfelkasten, der so hoch ist, dass der Geheimtext gerade hineinpasst. In diesen Kasten trägt
er spaltenweise in der Reihenfolge der Losungsnummern den Geheimtext ein und liest den Klartext
zeilenweise ab.
Wird ein Würfel-Geheimtext erneut mit einem (anderen) Würfel verschlüsselt, hat man das
Doppelwürfelverfahren."
Beispiel: Aus dem Klartext eintreffendersendungverspaetetneuerterminfolgt
wird mit dem Losungswort Schwarzwald der Geheimtext
rneregnfirsrtdeulnsptnveoedtmeeregteaefntnfuei ermittelt:
S C H W A R Z W A L D
8 3 5 9 1 7 11 10 2 6 4
------------------------
e i n t r e f f e n d
e r s e n d u n g v e
r s p a e t e t n e u
e r t e r m i n f o l
g t
------------------------
Verschlüsselt man den so erhaltenen Geheimtext wieder, diesmal mit dem Losungswort
Schwenningen, so ergibt sich der zweite Geheimtext als
ndeeelmtsvtrngieedffprugnennsefiteereertoarutn:
S C H W E N N I N G E N
11 1 5 12 2 7 8 6 9 4 3 10
--------------------------
r n e r e g n f i r s r
t d e u l n s p t n v e
o e d t m e e r e g t e
a e f n t n f u e i
--------------------------
Zusätzlich zum Doppelwürfel wird eine Cäsar Verschlüsselung gefordert. Diese Art der
Verschlüsselung wird hier nur zu Übungszwecken verwendet und sollte aufgrund ihrer extrem
geringen Sicherheit niemals ernsthaft eingesetzt werden. Diese Verschlüsselung verändert
lediglich die Buchstaben und lässt alle anderen Zeichen (Zahlen, Sonderzeichen, etc.) unverändert.
Schreiben Sie ein Programm, das den Spion bei seiner Verschlüsselungsarbeit unterstützt!
