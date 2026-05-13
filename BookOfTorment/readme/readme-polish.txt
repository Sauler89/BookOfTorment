======================================
PLANESCAPE: TORMENT - ENHANCED EDITION
MOD UI: Book of Torment v1.70
======================================

Instalacja zmienia pliki UI.menu, BGEE.lua, oraz L_pl_PL.lua.
Od wersji 1.50 te pliki będą patchowane, a więc w teorii zwiększa to kompatybilność BoT z innymi modami.

Przed instalacją pobierz:
https://forums.beamdog.com/discussion/64382/mod-journal-portrait-conversations-for-pstee/p1
(DWN: https://forums.beamdog.com/uploads/editor/w2/53k6wv7d6y0z.zip
https://web.archive.org/web/20230707040057/https://forums.beamdog.com/uploads/editor/w2/53k6wv7d6y0z.zip)
(Powyższy mod jest wymagany aby w "Book of Torment" były wyświetlane portrety w oknach dialogowych.)


WeiDU jest również wymagany do instalacji (od wersji 1.50):
https://github.com/WeiDUorg/weidu/releases
Po pobraniu zmień nazwę exe na Setup-BookOfTorment.exe

Instalacja (Windows&Wine):
1. Rozpakuj oba mody i wrzuć do folderu z grą (obok chitin.key); Struktura plików powinna wyglądać następująco: folder BookOfTorment (nie BookOfTorment/BookOfTorment) oraz plik exe.
2. Uruchom Setup-JournalPortraitConversations.exe (wybierz 'N' przy próbie [Modify PSTEE UI.Menu]), następnie 'I' zainstaluj;
3. Uruchom Setup-BookOfTorment.exe, zainstaluj.

Ustawienie skinów po instalacji: Przejdź do opcji grafiki w grze, i znajdź przycisk BoT ;).

---------------------------------------------------------------------------------------------------------------------------------
Uwagi: 
"Book of Torment" powinien być kompatybilny z innymi modami.

---

Twórca moda na portrety:

"Podczas instalacji lub reinstalacji tego moda na grze w toku rozgrywki, NPC w obszarach, które wcześniej odwiedziłeś, nie otrzymają portretów, ale obszary i NPC, których jeszcze nie odwiedziłeś, otrzymają portrety. Jeśli rozpoczniesz nową grę, wszystkie postacie niezależne będą miały portety."

https://forums.beamdog.com/discussion/64382/mod-journal-portrait-conversations-for-pstee

---------------------------------------------------------------------------------------------------------------------------------
Deinstalacja:
1. Jak podczas instalacji, tylko wybierz 'U'.

---------------------------------------------------------------------------------------------------------------------------------
Podziękowania za pomysł/inspiracje/pomoc dla: 
kanału discord - grimuar.pl(Grimuar Sferowca); Disco/smeagolheart/Pecca, Bubb, Argent77(kod do dodawania pvrz), lefreut(pomoc w ustawieniu kolorów w dialogach).

---------------------------------------------------------------------------------------------------------------------------------
Opis:
Początkowo modyfikacja powstała jako test i pytanie/potrzeba: bocznego okna dialogowego.

Mod powstał głównie metodą prób i błędów oraz copy/paste kodu, choć i nie bez pomocy życzliwych dusz obecnych na forach.   

-----------------------------------
Kolorowanie klikniętych odpowiedzi
-----------------------------------

Dodałem opcję kolorowania klikniętych odpowiedzi.

Ponieważ ta opcja zwiększa wagę pliku konfiguracyjnego Baldur.lua z ciągami znaków, nie jest pewne, czy i jak wpłynie to na grę;
więc jest to eksperymentalne i opcjonalne.

------------------------------------------------------
Jeśli chodzi o odchudzenie pliku conf: najprostszym sposobem jest usunięcie pliku Baldur.lua, gra utworzy go ponownie, ale należy pamiętać, że wszystkie ustawione opcje powrócą do wartości domyślnych.

Jeśli chcesz samodzielnie odchudzić plik conf: otwórz Baldur.Lua (w moich dokumentach), a następnie usuń każdy wpis zaczynający się od:

	SetPrivateProfileString('Graphics','Dlg Responses Color','1')
	SetPrivateProfileString('Dlg Color String','

Dzięki @bbminner za usprawnienia!

---
https://github.com/szef501/BookOfTorment/releases
https://www.nexusmods.com/planescapetormentenhancededition/mods/9
https://www.gibberlings3.net/forums/topic/36119-uimodplanescape-ee-book-of-torment-discover-the-dialogues-of-torment-in-a-new-edition/

szef, FallDamage312.

