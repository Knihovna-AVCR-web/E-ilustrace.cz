# iq-theme pro E-ilustrace

Tento repozitář obsahuje zdrojový kód pro WordPress šablonu s názvem **iq-theme**, vytvořenou speciálně pro projekt **E-ilustrace**.

## Obsah

- **404.php**: Stránka pro chybu 404.
- **category.php**: Šablona pro kategorie.
- **dist_old**: Staré vybuilděné assety.
- **index.php**: Hlavní šablonový soubor.
- **pageTemplates**: Složka s šablonami stránek.
- **single-event.php**: Šablona pro jednotlivé události.
- **style.css**: Hlavní CSS soubor pro stylování šablony.
- **assets**: Složka s nevybuilděnými assety.
- **dist**: Složka s vybuilděnými assety.
- **functions.php**: Funkce a hooky pro přizpůsobení WordPress šablony.
- **page.php**: Šablona pro jednotlivé stránky.
- **search.php**: Šablona pro vyhledávání.
- **single.php**: Šablona pro jednotlivé příspěvky.

## Instalace

1. Stáhněte si nebo naklonujte tento repozitář do složky `wp-content/themes`.
   ```sh
   gh repo clone Knihovna-AVCR-web/E-ilustrace.cz

2. Přejděte do adresáře s assety
   ```sh
   cd /wp-content/themes/iq-theme/assets

3. Spusťte npm script pro buildování assetů:
   ```sh
   yarn build

4. Vybuilděné assety se objeví ve složce `/wp-content/themes/iq-theme`. Ty je následně potřebné nahrát do adresáře `/wp-content/themes/iq-theme/dist`.


5. Promažte obsah temp složky:
   ```sh
   rm -rf /var/www/temp/*
