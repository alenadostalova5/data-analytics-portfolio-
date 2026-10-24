# Scrapování výsledků voleb (2017)
Jedná se o projekt napsaný v Pythonu, který stahuje výsledky voleb do Poslanecké sněmovny z roku 2017 z internetových stránek volby.cz. Je možné stáhnout jakýkoliv okres z daného webu a uložit jej do csv souboru.

# Jak program spustit
1.	Projekt stáhněte.
2.	Před jeho spuštěním je potřeba nainstalovat potřebné knihovny. K tomu můžete použít přiložený soubor requirements.txt a pak dejte do terminálu tento příkaz:
pip install -r requirements.txt

3.	Pro spuštění je potřeba zadat potřebný počet argumentů do terminálu na jeden řádek:
python main.py "https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103" "vysledky_nazevmesta.csv"
