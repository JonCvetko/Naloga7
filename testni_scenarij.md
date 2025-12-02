# Testni scenariji

---

## 1. Avtentikacija uporabnikov

**Koraki testa:**
1. Registriraj novega uporabnika.
2. Nato se prijavi z istimi podatki.

**Pričakovani rezultat:**
- Uporabnik je uspešno ustvarjen.
- Prijava vrne JWT in omogoči dostop do zaščitenih strani.

---

## 2. Nadzor omrežnih naprav

**Koraki testa:**
1. Po prijavi zaženi skeniranje omrežja.
2. Počakaj na seznam zaznanih naprav.

**Pričakovani rezultat:**
- Prikaže se seznam najdenih naprav z osnovnimi podatki (IP, MAC, status).

---

## 3. Analiza varnostnih ranljivosti

**Koraki testa:**
1. Izberi napravo s seznama.
2. Zaženi analizo ranljivosti.

**Pričakovani rezultat:**
- Prikaže se seznam morebitnih ranljivosti in priporočil.
