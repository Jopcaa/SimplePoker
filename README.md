# SimplePoker
Projekt "Simple Poker" za predmet Matematika z računalnikom.

# Pomoč za uporabo primerjave uspešnosti dveh začetnih rok

Parametri za zagon "pokersim.py" --hand1 --hand2 --community in pa število simulacij.

Roka je seszavljena iz ranka karte: A, K, Q, J, 10, 9, 8, 7, 6, 5, 4, 3, 2 in iz barve: c, s, h, d. (club, spade, heart, diamond)

Karta formata Xx je poljubna karta in je uporabljena samo za skupne karte.

Primer uporabe(--community lahko prazen):

python pokersim.py --hand1 AcTd --hand2 Qh5s --community XxXxXxXxXx 1000

ali 

python pokersim.py --hand1 AcTd --hand2 Qh5s 1000
