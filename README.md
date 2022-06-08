# Penzion u vody

Tentokrát jsme jako podklad dostali kompletně nakódovaný web o pěti stránkách. Naším úkolem bylo udělat z něho Eleventy projekt, z částí stránky společných pro celý web udělat šablonu, ve stránkách samotných nechat pouze obsah a vše nastavit tak, aby výsledkem byl opět hotový a funkční web. Tento web jsme pak vystavili na Netlify.

![Ukázka výsledku](ukazka-vysledku.jpg)


Cíl úkolu

Cílem tohoto úkolu je hlavně vyzkoušet si základní práci s generátorem statických webů Eleventy:

Práce s Eleventy

  - součástí zadání je kompletně nakódovaný pětistránkový web (HTML, CSS, obrázky)
  - proveď v projektu `npm init` a nainstaluj Eleventy
  - nakonfiguruj Eleventy podle instrukcí v lekci **Eleventy - konfigurace** (hlavně aby se do sestaveného webu kopírovaly složky `css` a `images`)
  - v sekci `scripts` souboru *package.json* vytvoř dva skripty `build` a `serve`
  - spusť web lokálně pomocí skriptu `serve` a vyzkoušej, zda vše funguje správně
  
Vytvoření šablony

  - všech pět stránek webu má společnou hlavičku a patičku
  - vytvoř ze společných částí šablonu podle instrukcí v lekci **Eleventy - První šablona**
  - v HTML stránkách nech pouze obsah unikátní pro danou stránku
  - do stránek přidej **front matter** a nastav stránky tak, aby používaly vytvořenou šablonu
  - v HTML (v šabloně i v obsahu) a v CSS uprav cesty k obrázkům, stylům, apod. tak, aby začínaly lomítkem a ukazovaly na správné soubory
  - v šabloně uprav menu, aby ukazovalo na správné adresy stránek, až Eleventy vygeneruje výsledný web
  
Práce s Gitem
  - ověř, že v souboru *.gitignore* ignorujeme složku *_site* a *node_modules*, protože ani jednu z nich v Gitu nechceme ukládat
  - proveď commit a push řešení na GitHub
 
Netlify

  - pokud ještě nemáš, tak si vytvoř účet na [Netlify](https://netlify.com)
  - na Netlify si založ nový web podle instrukcí v lekci **Eleventy - Publikování na Netlify**
  - jako zdroj pro vytvořený web nastav svůj GitHub repozitář s tímto úkolem
  - pokud se na Netlify podaří web sestavit a publikovat, zkopíruj jeho adresu a vlož ji do popisu GitHub repozitáře, aby koučové mohli zkontrolovat, zda ti web na       Netlify opravdu běží




