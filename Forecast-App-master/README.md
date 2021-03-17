# P-edpov-d-po-as-App

Aplikace zobrazuje předpověď počasí, data čerpá z API adresy https://openweathermap.org/
Zobrazuje aktuální teplotu + předpověď na 5 následujícíh dní. Zobrazí se tedy předpovídaná teplota a k tomu popis počasí.

Počasí lze vyhledávat dle měst, které se listují z přiloženého souboru citi.list.json. Toto vyhledávání funguje na LiveServeru. Funguje pomocí funkce fetch().Pokud se začne psát do vyhledávače, objeví se vždy 5 prvních měst, které se shodují s textem ve vyhledávači.
