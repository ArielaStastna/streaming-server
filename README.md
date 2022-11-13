# streaming-server
• Vytvořte šablonu a metodu index, která bude obsahovat formulář:
• Zde bude text input pro zadání URL videa
• Checkbox pro muted a autoplay
• Další input pro zadání šířky videa (bez zadání bude šířka 1000px)
• Po odeslání metodou POST požadavek zpracuje další metoda na adrese /player
• Metoda player bude obsahovat potřebnou logiku (model, potřebné if…)
• Výsledkem bude šablona player.html, kde se bude přehrávat video podle nastavených
parametrů, zadaných ve formuláři.
• Video element bude využívat atribut poster=url obrázku (viz níže)
• Když se nezadá žádné URL, tak se místo videa zobrazí vlastní error zpráva ve vlastním
stylu: Např: Nebyla zadána žádná adresa videa!
• Nad videem bude nadpis „Přehrávání MP4 streamu: vaše příjmení, případně i ID“
