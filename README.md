# Web o čajích (statický)

## Příprava

1. Přihlas se **v terminálu** na server TuX a přesuň se do adresáře `~/www`
2. Gitem naklonuj repozitář `https://github.com/edumach/caj1`
3. Tím vznikne adresář `~/www/caj1/`
    ```
    $ cd www
    $ git clone https://github.com/edumach/caj1
    cd caj1
    ```
4. Zkontroluj funkčnost webu na URL `https://tux.panska.cz/~10XPrijmeniJ/caj1`



## Struktura
    
- **HTML soubor s pevně definovaným obsahem**.
- Každý čaj je přímo vložen do HTML jako samostatná sekce.
- Obsah se nemění bez manuální úpravy kódu.

## Konstrukční prvky
    
**HTML základ:**
- `<!DOCTYPE html>` – definice typu dokumentu.
- `<head>` – meta informace (kódování UTF-8, titulní název stránky).
- `<body>` – obsah stránky (nadpisy, odstavce, obrázky).

**Struktura obsahu:**
- Hlavní nadpis (`<h1>`) – název stránky.
- Popisný text (`<p>`) – úvodní informace.
- Sekce pro každý čaj (`<h2>`, `<img>`, `<p>`).
- Oddělení čajů (`<hr>` – vodorovná čára).

**Statický copyright:**
- Pevný rok nebo jednoduchý text na konci stránky.

## Úkoly (jsou DVA a prolínají se)

Web obsahuje jeden vzorový článek o černém čaji. Podle stejného schématu a struktury přidej na stránku další dva čaje. Vhodné obrázky a doprovodné texty si dohledej na webu [www.vybornycaj.cz](https://www.vybornycaj.cz). Pak pokračuj další částí (v tomto pořadí):

1. Do projektu přidej obrázek a vytvoř kód pro zobrazení druhého čaje.
2. Vytvoř commit "Doplnění o <název> čaj"
3. Do projektu přidej obrázek a vytvoř kód pro zobrazení třetího čaje.
4. Vytvoř commit "Doplnění o <název> čaj"
5. Pod každý z čajů přidej hypertextový odkaz na články o tomto čaji. Ten bude vložený v odstavci. Text bude pro každý ze tří odkazů stejný: "Více informací".
6. Vytvoř commit "Doplnění odkazů"

## Odevzdání a hodnocení

Z cvičení budou celkem dvě známky:

1. Funkční web na URL: `https://tux.panska.cz/~10XPrijmeniJ/caj1`.
2. Git commity. Kontrolu si provedu přímo na serveru.

