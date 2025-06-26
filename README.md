# Lexikalische-Permutationschiffre
- basiert auf semantischer Substitution
- live demo: https://easypx.github.io/Lexikalische-Permutationschiffre/

**🧪 3. Sicherheitsstärke im historischen Vergleich**

Das System ist vergleichbar mit einem mechanischen Einmal-Wort-Chiffriergerät, wie es etwa beim diplomatischen Verkehr in der Zwischenkriegszeit eingesetzt wurde – robust, aber nur so sicher wie die Geheimhaltung der Zuordnung und des Schlüssels. Allerdings ist durch die gegebene Mehrdeutigkeit der Loesungen bei einer Brute Force Attacke eine eindeutige Zuordnung praktisch unmoeglich. 

Moderne Sicherheitsbewertung:

Angriffsmethode	Erfolgschance ohne Seed
- Brute-Force (32-bit Seed)	- realistisch, aber mehrdeutig!
- Brute-Force (Passphrase)	- praktisch null
- Häufigkeitsanalyse - ineffektiv (bei Wortersetzung)
- Known-Plaintext-Angriff	- möglich bei sehr langem Text
- Dictionary-Angriff	- nur mit massivem Kontext möglich
