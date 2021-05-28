Hogy lehessen használni a Highscore rendszert, a programot egy live szerver segítségével kell elindítani, mert anélkül nem működnek a cookie-k amiben tárolva vannak a highscore adatai.
Itt van amit én használok: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
A kód gameplay részét egy random oldalról másoltam ki, majd fejlesztettem tovább:
-Megcsináltam, hogy a snake át tudjon menni a falon a játékrész túloldalára
-Beleraktam egy restart rendszert, hogy ha valaki veszít akkor helyből újra lehessen indítani, ne kelljen újratölteni a weboldalt
-Beleraktam a highscore rendszert
-Felnagyítottam a kijelzőt, mert az eredetin szinte semmit nem lehetett látni
-A stílusokat a style.css-be raktam bele, hogy jobban átlátható legyen

Note: A programot 21:9-es monitorra optimalizáltam, lehet hogy 16:9-ben a highscore szöveg vagy valami egyéb elem nem látható, el van takarva. Ezt a style.css-ben meg lehet változtatni.