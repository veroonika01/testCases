

###Testovací prípad TC- kompletný proces objednania tovaru na stránke [https://www.saucedemo.com/inventory.html]

**Predpoklady**: používateľ je zaregistrovaný a má vytvorený aktívny účet s loginom a heslom

---

###Testovacie kroky##


1. **Prihlásenie používateľa**:
Otvor webový prehliadač a prejdi na URL [https://www.saucedemo.com/inventory.html]
Zadaj svoje prihlasovacie údaje (používateľské meno a heslo).
Klikni na tlačidlo Login.
Ak sú údaje správne, používateľ bude úspešne prihlásený a presmerovaný na hlavnú stránku.

2. **Zobrazenie produktov**:
Na hlavnej stránke sa zobrazí zoznam dostupných produktov, pričom každý produkt má uvedený názov, popis, cenu a tlačidlo "Add to Cart" na pridanie do košíka.

3. **Pridanie produktu do košíka**:
Používateľ vyberie požadovaný produkt a klikne na tlačidlo "Add to Cart".
Po pridaní produktu sa tlačidlo zmení na Remove, čo indikuje, že produkt bol úspešne pridaný do nákupného košíka.
V pravom hornom rohu sa aktualizuje ikona nákupného košíka a zobrazuje počet pridaných položiek.

4. **Kontrola obsahu nákupného košíka**:
Kliknutím na ikonu košíka je používateľ presmerovaný do sekcie "Your Cart".
V tejto sekcii sa zobrazuje zoznam pridaných produktov vrátane ich názvu, množstva a ceny.

5. **Pokračovanie k pokladni**:
Používateľ má možnosť pokračovať v nákupe cez tlačidlo "Continue Shopping" alebo prejsť na pokladňu kliknutím na tlačidlo "Checkout".
Zvoľ možnosť "Checkout"

6. **Vyplnenie údajov objednávky**:

Používateľ je presmerovaný na stránku Checkout: Your Information, kde zadá požadované informácie do textových polí:
First Name: Meno používateľa.
Last Name: Priezvisko používateľa.
Postal Code: Poštové smerové číslo.
Po vyplnení údajov klikne na tlačidlo Continue.

7. **Súhrn objednávky**:
Stránka Checkout: Overview zobrazí kompletný prehľad objednávky, ktorý zahŕňa:
Zoznam objednaných produktov s názvami, množstvom a cenami.
Informácie o platbe (napr. kreditná/debetná karta).
Informácie o doprave (prepravná spoločnosť a cena dopravy).
Celkovú sumu, vrátane dane a dopravy.

8. **Dokončenie objednávky**:
Používateľ môže dokončiť alebo zrušiť objednávku výberom jednej z dvoch možností:
Kliknutím na Cancel sa objednávka zruší a používateľ bude presmerovaný na domovskú stránku.
Vyber druhú možnosť a klikni na tlačido Finish na dokončenie objednávky.
Kliknutím na Finish sa objednávka úspešne dokončí a zobrazí sa hlásenie Checkout: Complete! s potvrdením Thank you for your order!.

9. **Návrat na domovskú stránku**:
Používateľ klikne na tlačidlo Back Home a je presmerovaný späť na hlavnú stránku.

10. **Odhlásenie používateľa**:
Používateľ klikne na ikonu Hamburger-menu v ľavom hornom rohu a z ponuky vyberie možnosť "Logout".
Po odhlásení je používateľ presmerovaný na úvodnú stránku s prihlásením.


---



##### Výsledok testu: Pass/Fail
