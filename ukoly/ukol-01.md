# ukol-01

Hlavním cílem úkolu z první lekce je vyzkoušet si systém odevzdávání (viz [návod](../ODEVZDAVANI-UKOLU.md)). Pokud do příští lekce
nevyřešíš úlohu, odevzdej alespoň testovací soubor, abychom věděli, že víš jak na to.

V případě dotazů vždy můžeš kontaktovat kouče ve Slackovém kanálu tvé skupinky.

---

## Zadání:

Napiš program, který bude obsahovat jednu proměnnou `jmeno`. Tato proměnná bude obsahovat libovolné křestní jméno (třeba tvoje).
Tvůj program vytvoří e-mailovou adresu na základě této proměnné, s doménou `czechitas.cz` a tuto e-mailovou adresu vypíše.

Tedy pokud bude hodnota proměnné `jmeno` například `Jindřiška`, pak program vypíše `Jindřiška@czechitas.cz`.

--- 

## Nepovinný bonus:

*Tuto část můžeš řešit, pokud už máš první část úkolu hotovou a chceš si ještě něco procvičit.*

Napiš program, který bude obsahovat proměnnou `jmeno_a_prijmeni`. Obsah proměnné načti od uživatele pomocí funkce `input`. 
Tvůj program postupně vypíše několik způsobů formátování jména:
* všechna písmena velká (vypíše např. `JANA MALÁ`)
* všechna písmena malá (vypíše např. `jana malá`)
* standardní varianta - první písmeno velké, další malá (vypíše např. `Jana Malá`)
* iniciály (vypíše např. `J. M.`)
* křestní jméno zkrácené na první písmeno a příjmení, pokud je křestní jméno delší než 5 znaků. Jinak vypíše standardní variantu, tj. první písmeno velké, další malá
(u vstupu `Jarmila Malá` by došlo ke zkrácení křestního jména, zatímco u vstupu `Jana Malá` nikoliv)

Zaexperimentuj s různými vstupy od uživatele (co třeba `JaNA maLá`?).
