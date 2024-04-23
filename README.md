# Tower Defense Arrow

## Popis hry

Tower Defense Arrow je akční strategická hra, ve které hráč brání svou základnu před neustále se zvyšujícími vlnami nepřátel. Hra se zaměřuje na plánování, strategii a rozhodování.
největší inspirace pro tuto hru jsou: Bloons TD a Kingdom Rush.

**Pro koho tato hra je:**
Tower Defense Arrow je vhodná pro hráče, kteří si užívají strategické výzvy a plánování taktiky. Díky jednoduché, avšak zábavné hratelnosti je ideální pro casual hráče, kteří si chtějí užít krátké herní sezení.

**Unity:**  
Tower Defense Arrow bude vyvíjena v Unity kvůli jeho vhodným nástrojům a prostředí pro tvorbu her.


## Herní mechaniky

1. **Systém peněz:**
   - Hráč získává peníze za každého zabitého nepřítele.
   - Peníze se používají k výstavbě a vylepšení obranných věží.
   - Po dokončení každého kola hráč dostane základní odměnu (za 1. vlnu 50 peněz), která se zvyšuje s každým dalším kolem o 25%.
   - Po každých 15 kolech se odměna za zabití nepřítele zdvojnásobí.
   - hráč začíná s 100 penězi

2. **Systém věží:**
   - Hráč má možnost umístit obranné věže na levelu 1 na herní pole, kromě cesty na které putují nepřátelé.
   - Každá věž může být vylepšena ve dvou oblastech: síla útoku (oranžová koule) a dosah střelby (modrá koule).
   - Po pěti libovolných vylepšení se věž změní na level 2, která bude mít +1 ke každému vylepšení.
   - Po dalších deseti vylepšení se věž změní na level 3, která bude mít +2 ke každému vylepšení.
   - Vzlepšování věží:
   - Když najede hráč myškou na věž, zobrazí se mu nabídka pro vylepšení síly (oranžová koule) a nebo dohledu (modrá koule).


3. **Systém nepřátel:**
   - Hra obsahuje tři hlavní typy nepřátel: Knight, Rogue a Mutant.
   - Nepřátelé se pohybují po předem definované cestě na herním poli směrem k základně hráče.
   - Hra začne jen s jedním typem a to Knightem, který má základní speed a 5HP
   - Každé páté kolo se jeho HP zvýší o 1 a jeho rychlost o 5%
   - 5. kolo se přidá další typ a to rogue, který je 2x rychlejší než knight ale má 2 HP a každé 5. kolo se mu rychlost zvýší v souladu s knightem tudíž (po deseti kolech bude mít knight rychlost 1,1 a rogue 2,2)
   - 10. kolo se přidá poslední typ nepřátele, mutant, který má 10HP, ale jen polovinu rychlosti knighta. Stejně jako rogue se mutantu každé 5. kolo zvíší jeho hp o 3 a jeho rychlost v souladu s knightem 

4. **Herní ovládání:**
   - Hráč může přetáhnout věže z menu na herní pole.
   - Po najetí myší na věž se zobrazí nabídka vylepšení které si může hráč zakoupit.
   - Hráč může také spouštět vlny nepřátel klávesnicí "space" po zneškodnění polovyny současné vlny
   - Hráč má také možnost spustit tzv. autoplay, který pustí další vlnu po zneškodnění všech nepřátel současné vlny

5. **Spouštění vln:**
   - První vlana se musí spustit jen hráčem klávesou "space"
   - Po každé splněné vlně hráč může  spustit další vlnu klávesou "space"
   - Hráč má také možnost spustit vlnu ještě před tím, než první splnil a to když v první vlně zneškodní polovinu nepřátel, poté hráč může spustit další vlnu klávesou "space"
   -  Hráč má také možnost spustit tzv. autoplay, který pustí další vlnu po zneškodnění všech nepřátel současné vlny
   - Po zneškodnění všech nepřátel vlny hráči dostane možnost pokračovat do další vlny. Existuje také možnost zapnutí režimu autoplay.
  
   
##Technické parametry:
   - Kamera ve hře je ve sklomnu 30°
   - všechny animace jsou ve 30FPS
     
  
