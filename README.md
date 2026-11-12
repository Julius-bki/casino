# Zur Goldenen Elster

Ein Spielgeld-Casino in einer einzigen HTML-Datei: 36 Spiele, darunter 17 Automaten, Texas Hold’em gegen drei Computergegner, Roulette, Blackjack und Beutekisten.

Neu dabei:

- **Diebesgut:** ein Automat mit 6 × 5 Feldern ohne Linien. Fünf gleiche Beutestücke, die sich berühren, gewinnen und rutschen nach. Jedes Gewinnfeld wird zu Gold, und eine Lupe deckt darunter Münzen und Beutesäcke auf. Drei Elstern starten den Raubzug, in dem das Gold liegen bleibt. Quote ca. 96,7 % (3 Mio. simulierte Runden).
- **Pferderennen:** sechs Pferde, Sieg- und Platzwetten, jedes Rennen ein neues Feld. Jede Quote zahlt auf Dauer 96 %.
- **Schollensprung:** Ein Pinguin springt über zehn Reihen Eisschollen, manche brechen. Vier Schwierigkeiten, 97 %.
- **Drei-Karten-Poker:** Ante, Paar-Plus, spielen oder passen. Exakt gerechnet 96,6 % aufs Ante, 97,7 % auf Paar-Plus.
- **Kartenkrieg:** Die höhere Karte gewinnt, bei Gleichstand Krieg oder Aufgeben. Sechs Decks, exakt 97,1 %.

Alle Spiele haben eigene Namen, eigene Regeln im Detail und ein eigenes Aussehen.

Die Symbole sehen aus wie an einem klassischen Spielautomaten: kräftige Farben, dunkle Kontur und Glanzlicht. Die Kacheln haben einen Goldrahmen mit Lauflicht aus Glühbirnen. Die Umrisse stammen von game-icons.net (CC BY 3.0, gezeichnet von Lorc, Delapouite und anderen). Der Bildnachweis mit allen Zeichnern steht auf der Seite unter „Bildnachweis“.

In den zehn neuesten Automaten gibt es Glücksdrehungen: Etwa jede 33. Drehung bekommt einen Multi (×2 bis ×10), etwa jede 50. eine wilde Walze (×2 bis ×5).

In der Drachenhöhle wecken drei Dracheneier den Drachen. Dann gibt es Wild Spins in fünf Stufen: Wild, Super Wild, Mega Wild, Ultra Wild und Inferno Wild Spins. In jeder Stufe brennen mehr Walzen, ganz oben die Walzen 2 bis 5. Jedes Ei in den Freispielen füllt die Glut, und drei Eier heben die Stufe. Jede Stufe hat ihr eigenes Feuer, mit Drachen-Intro, Funkenregen und wackelndem Bildschirm.

Dazu ein Levelsystem: Jede Runde bringt Erfahrung, jedes Level bringt Token. Für Token gibt es Ausrüstung, die das Glück leicht hebt. Mit Talern wertest du sie bis Stufe 10 auf, und jede Stufe kostet doppelt so viel wie die vorige (alles voll: +5 % Glück). 36 Erfolge bringen weitere Token.

Der Shop heißt Schatzkammer (goldenes + neben der Börse). Er hat drei Bereiche:

- **Vitrinen:** Gamepässe (Turbo-Hebel, VIP-Ausweis, Goldrahmen), Erfahrungstrank, Glückskeks, Wundertüte, Tagesangebot und eine Gratis-Tageskiste.
- **Für Automaten:** Gutscheine für Freispiele, Glücksdrehungen und Drehpakete.
- **Dein Besitz:** alles, was du schon hast.

Gekauft wird ohne Zusatzfenster: Der erste Klick auf den Preis fragt nach, der zweite kauft. Keine Quote im Shop liegt über 100 %.

Es gibt nur Spielgeld (Taler). Nichts davon ist echtes Geld, und man kann nichts kaufen oder auszahlen. Der Spielstand liegt im Browser (localStorage). Wird er einmal ungültig, repariert die Seite ihn beim Laden selbst und legt den alten Stand als Sicherung daneben.

Spielen: https://julius-bki.github.io/casino/
