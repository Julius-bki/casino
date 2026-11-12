# Zur Goldenen Elster

Ein Spielgeld-Casino in einer einzigen HTML-Datei: 42 Spiele, darunter 23 Automaten, Texas Hold’em gegen drei Computergegner, Roulette, Blackjack und Beutekisten.

Neu dabei:

- **Fünf Automaten mit fünf neuen Mechaniken.** Alle Quoten sind exakt gerechnet und liegen bei ca. 96 %:
  - **Anglerglück (Sammler):** Goldfische tragen Werte bis zum 50-fachen Einsatz, jeder Angler holt sie alle ein. In den Freispielen gibt es dreimal so viele Goldfische, und je vier Angler bringen zehn Freispiele mehr und heben die Fänge auf ×2, ×3 und ×5.
  - **Maskenball (Zwillingswalzen):** Bei etwa jeder achten Drehung werden zwei bis fünf benachbarte Walzen zu Zwillingen und zeigen dasselbe. In den acht Freispielen sind es bei jeder Drehung drei bis fünf.
  - **Urzeittal (Riesenwalze):** Die Walzen 2 bis 4 zeigen bei jeder Drehung ein einziges Symbol in 3 × 3, ein Riesen-Vulkan sind neun Joker. In den Freispielen gibt es nur noch Saurier.
  - **Jahrmarkt (Glücksrad):** Drei Glücksräder drehen das große Rad mit zwölf gleich großen Feldern. Das Feld „Hoch!“ führt aufs Goldrad mit bis zu 2.500-fachem Einsatz. Das Rad gibt es auch im Shop zu kaufen.
  - **Zuckerbäckerei (Naschen):** In den Freispielen naschen je drei Schneebesen das schwächste Symbol von den Walzen, erst B, D, K und A, dann Bonbon und Lolli. Jedes Mal gibt es zwei Freispiele mehr.
- **Big-Player-Pokertische:** Zwei neue Hold’em-Tische mit 250/500 und 1.000/2.000 ohne Limit. Du nimmst deine ganze Börse mit, Nachkaufen geht ohne Obergrenze, und jeder Gegner bringt vor jeder Hand mindestens so viel mit wie du. Die drei normalen Tische bleiben bei höchstens 100 großen Blinds.
- **Ritterburg:** ein Ritter-Automat mit 5 Walzen und 20 Linien. Das Schwert ist der Joker, drei Kelche öffnen zehn Freispiele. Dort wächst jedes Schwert über seine ganze Walze, und jede Drehung mit Gewinn hebt den Faktor um eins, bis ×10. Drei neue Kelche bringen zehn Freispiele mehr. Quote ca. 96 % (Freispiele mit 200.000 Runden simuliert).
- **Diebesgut:** ein Automat mit 6 × 5 Feldern ohne Linien. Fünf gleiche Beutestücke, die sich berühren, gewinnen und rutschen nach. Jedes Gewinnfeld wird zu Gold, und eine Lupe deckt darunter Münzen und Beutesäcke auf. Drei Elstern starten den Raubzug, in dem das Gold liegen bleibt. Quote ca. 96,7 % (3 Mio. simulierte Runden).
- **Pferderennen:** sechs Pferde, Sieg- und Platzwetten, jedes Rennen ein neues Feld. Jede Quote zahlt auf Dauer 96 %.
- **Schollensprung:** Ein Pinguin springt über zehn Reihen Eisschollen, manche brechen. Vier Schwierigkeiten, 97 %.
- **Drei-Karten-Poker:** Ante, Paar-Plus, spielen oder passen. Exakt gerechnet 96,6 % aufs Ante, 97,7 % auf Paar-Plus.
- **Kartenkrieg:** Die höhere Karte gewinnt, bei Gleichstand Krieg oder Aufgeben. Sechs Decks, exakt 97,1 %.

Alle Spiele haben eigene Namen, eigene Regeln im Detail und ein eigenes Aussehen.

Die Symbole sehen aus wie an einem klassischen Spielautomaten: kräftige Farben, dunkle Kontur und Glanzlicht, auch die Sieben und die Kartenwerte A, K, D, B. Die Kacheln haben einen Goldrahmen mit Lauflicht aus Glühbirnen. Die Umrisse stammen von game-icons.net (CC BY 3.0, gezeichnet von Lorc, Delapouite und anderen). Der Bildnachweis mit allen Zeichnern steht auf der Seite unter „Bildnachweis“.

In den sechzehn neuesten Automaten gibt es Glücksdrehungen: Etwa jede 33. Drehung bekommt einen Multi (×2 bis ×10), etwa jede 50. eine wilde Walze (×2 bis ×5). Im Urzeittal gibt es nur Multis, weil die Riesenwalze schon drei Walzen füllt.

In der Drachenhöhle wecken drei Dracheneier den Drachen. Dann gibt es Wild Spins in fünf Stufen: Wild, Super Wild, Mega Wild, Ultra Wild und Inferno Wild Spins. In jeder Stufe brennen mehr Walzen, ganz oben die Walzen 2 bis 5. Jedes Ei in den Freispielen füllt die Glut, und drei Eier heben die Stufe. Jede Stufe hat ihr eigenes Feuer, mit Drachen-Intro, Funkenregen und wackelndem Bildschirm.

Dazu ein Levelsystem: Jede Runde bringt Erfahrung, jedes Level bringt Token. Für Token gibt es Ausrüstung, die das Glück leicht hebt. Mit Talern wertest du sie bis Stufe 10 auf, und jede Stufe kostet doppelt so viel wie die vorige (alles voll: +5 % Glück). 36 Erfolge bringen weitere Token.

Der Shop heißt Schatzkammer (goldenes + neben der Börse). Er hat drei Bereiche:

- **Vitrinen:** Gamepässe (Turbo-Hebel, VIP-Ausweis, Goldrahmen), Erfahrungstrank, Glückskeks, Wundertüte, Tagesangebot und eine Gratis-Tageskiste.
- **Für Automaten:** Gutscheine für Freispiele, Glücksdrehungen und Drehpakete.
- **Dein Besitz:** alles, was du schon hast.

Gekauft wird ohne Zusatzfenster: Der erste Klick auf den Preis fragt nach, der zweite kauft. Keine Quote im Shop liegt über 100 %.

Es gibt nur Spielgeld (Taler). Nichts davon ist echtes Geld, und man kann nichts kaufen oder auszahlen. Der Spielstand liegt im Browser (localStorage). Wird er einmal ungültig, repariert die Seite ihn beim Laden selbst und legt den alten Stand als Sicherung daneben.

Spielen: https://julius-bki.github.io/casino/
