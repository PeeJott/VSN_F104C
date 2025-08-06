VSN F-104C Starfighter (Standalone) V 2.9.16.099ea

CREDITS
*******
Modell lizensiert von					- Gerritboom

3d:
 - Modellierung, Animationen (extern)			    - cdpkobra, Razor, PeeJott,
 - Modellierung/Änderung Cockpit (intern)			- Reign, cdpkobra, PeeJott  
 - Cockpit Textur					                    - CGTrader, PeeJott, cdpkobra
 - Cockpit Integration/Animation (NEW)			  - cdpkobra, PeeJott
 - Modellaktualiesierungen				            - Soulfreak
 - Modell crewladder					                - TOMs Modelling in Motion - www.youtube.com/c/tomgrigat

Textuen:
 - RoughMet Dateien 					  - cdpkobra/PeeJott
 - VSN_F104G_psd_template				- file404
 - Liveries						          - jocko417
 - Liveries (F-104G orig)				- Soulfreak, JP Gabobo

Sounds:
 - Cockpit						- Shutter, PeeJott
 - external						- ViolentNomad, PeeJott

C++
 - EFM						                      - PeeJott (in some parts based on A-4 EFM, please see below!)
 - EFM Unterstützung (F-104C)				    - Copprhead, Firebird
 - EFM unterstützung (F-104G orig)			- JNelson, TheRealHarold,

Lua-Systems:
 - Radar and Gunpipper				- Copprhead (Radar based on simlpeRadarExample by Nero)
 - RWR						            - PeeJott (based on simpleRWRExample by Nero)
 - SRS integration					  - Streakeagle
 - rest						            - PeeJott (with some tips and clues from DCS Modding Hub Discord -> you are legends!)

Weapons:
 - BDU-36 and B61-4 (Modeling + System)			- Marco1985

Test-Teams:
 - Test-Team (F104G orig)				- GVAD, Talo, Niclas, Kingsnake, 
 - Test-Team (F-104C)					-  Jimbo, Streakeagle, Kingsnake, DarkWebLesbian, Spikef22

Menu:
 - Icons 						- PeeJott
 - Theme						- PeeJott
 - Music						- Music by ComaStudio from Pixabay

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
If someone was forgotten to be mentioned, please contact us and we will get you the credit you deserve :-)

Wenn ich jemanden vergessen habe, bitte bei mir melden und ich trage es ein.

################################# EFM Licensing ################################################
GPL-3 License:

The EFM-Code (C++) is licensed under the GPL-3 license, which you can find here https://www.gnu.org/licenses/gpl-3.0.de.html
That means, basically, that you are allowed to use the code, or snippets or parts of the code in your projects, but need to name the author of the code, 
you are using it from. Since the GPL-3 License kind of got handed down from The A-4 comunity mod, from which some parts of EFM code are derived from, 
it would be the right move to name VSN (PeeJott) AND the A-4 comunity-mod-team as the ones who licensed the use of the code. You should point out the 
changes you made to the code, where you should compare your code to the code you used, in this case VSN, since you can't now the differences between 
this code and A-4 code. That way everybody should be able to know what changes were made from codebase to codebase. This applies to (in our opinion) 
significant changes, not every minor detail since that makes no real sense and would rather lead to confusion and not clarification.
You will have to provide the source code in one form or the other with your software or publicly in a different way. You may not sell the parts of software
that you got from the codebase here, since only non commercial use is allowed. This is meant as a kind of "safe-keeping" yourself and us from claims 
that might arise by the usage of GPL-3 licensed code-parts, since after a while it is pretty easy to lose track and there is always the possibility that someone 
originally did not accept a certain kind of usage, and after some years, nobody does remember that persons take on this matter. 
So better steer safe of that problem in the first place.

This EFM (source-code) is downloadable from:

https://drive.filen.io/f/8ba4c168-a6e3-4863-939f-5fa0bba91d7c#lWYJm8M7n0L3ye3yTkWc0VxPuyiT0dab
#################################################################################################
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Das 3D-Modell des F-104G Starfighter basiert auf 3D-Daten von file404, die über Turbosquid erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104S Starfighter basiert auf 3D-Daten von file404, die über Turbosquid erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104 Starfighter Cockpit basiert auf 3D-Daten von Tolis die erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104 crewladder basiert auf 3D-Daten von TOMs Modelling in Motion die erworben und als Referenz in der Modellierung verwendet wurde.

Der Quellcode des EFM steht unter der im dortigen Unterordner eingebrachten Lizenz. Die Weiterverwendung und Verbreitung des Quellcodes unterliegt den dort abgedruckten Lizenzbestimmungen.
Der Quellcode ist zum download verfügbar im F-104G Discord oder per Kontaktnachricht an PeeJott über das LockOn-Forum.



KONTAKTDATEN
************

cdpkobra
lockonforum.de
https://lockonforum.de/user/711-cdpkobra/#sitemap_cms

ED Forum:
https://forums.eagle.ru/member.php?u=88910


11.11.2021

- F-104C Hinzugefügt
- Crewladder
- Tanksonde
- 1960s - 1970s era Pilot

Liveris:
custom_args =
{
    [70] = 0.0, 	-- 0.0 = F-104G / 0.3 = F-104C / 0.45 = CF-104 Early / 0.5 = CF-104 / 1.0 = F-104S
	[801] = 0.0, 	-- 0.0 = Martin Baker seat / 1.0 = C-2 seat
	[802] = 1.0, 	-- 0.0 = Modern pilot / 1.0 = 1960s - 1970s era Pilot
	[803] = 0.0, 	-- 1.0 = Tanksonde
}



15.10.2021

VSN_F104G 2.7.5.01

- F-104G EFM
- F-104G Cockpit
- VSN_F104G_AG entfernt
- Flugzeug Auswahl wird in der Liveris erstellt.

custom_args =
{
    [70] = 0, -- F-104G=0 / CF-104=0.45 Early / CF-104=0.5 / F-104S=1
    [801] = 0.0, --C-2 seat=1.0
}



14.04.2020

VSN_F104G 2.5.6.02
- VSN_F104S + VSN_F104S_AG hinzugefügt
- psd_template der F-104S hinzugefügt (VSN_F104G-S_psd_template.zip)

VSN_F104G 2.5.4.02
- Textur Fehler im Bereich des Hud korrigiert
- Textur Auflösung 4096

VSN_F104G 2.5.4.01
- Tank korrigiert.
- Skins hinzugefügt
- CMD hinzugefügt (Avionik Auswahl)
- AG Waffen hizugefügt.

DCS 2.5.4 Beta1 FREEWARE RELEASE


Dieser Mod benötigt das DCS: Flaming Cliffs 3 (FC3) Modul 
https://www.digitalcombatsimulator.com/de/shop/modules/dcs_flaming_cliffs_3/

Installation Anleitung
**********************
https://lockonforum.de/community/thread/7521-mods-richtig-installieren/
https://lockonforum.de/community/thread/6667-flyable-fc3-flieger-mit-3d-f-15c-cockpit/


RECHTLICHER HINWEIS
*******************
Dieser VSN_F104G Mod ist FREEWARE.
Das gesamte Originalmaterial ist urheberrechtlich geschützt und darf nicht ohne Genehmigung verwendet werden.
Das Umpacken oder Modifizieren dieses Pakets und seines Inhalts ist ohne Genehmigung nicht gestattet.
Die Verbreitung dieser Datei im Internet oder auf anderen Medien ist erlaubt, sofern sie kostenlos und ohne Veränderung der Originaldatei erfolgt.
Jede Art von Verteilung, die den Tausch von Geld beinhaltet, ist ohne Genehmigung nicht erlaubt.

Diese Software wird ohne jegliche ausdrückliche oder stillschweigende Garantie vertrieben. 
Diese Software sollte und wird keine Schäden an Ihrem System verursachen, dennoch ist der Autor nicht verantwortlich, für alle Schäden, die durch diese Software verursacht wird.

Das in diesem Modell dargestellte geistige Eigentum, einschliesslich der Marke "Lockheed F-104 Starfighter", ist nicht mit den ursprünglichen Rechteinhabern verbunden oder wird von diesen unterstützt.

Dieser Mod enthält lizenzfreie Texte aus Wikipedia.

CREDITS
*******
Gekauft von					        - Gerritboom
VSN_F104G Mod					      - cdpkobra
EFM						              - PeeJott
EFM unterstützung					  - JNelson, TheRealHarold, Firebird, A4-Team
Aerodynamics-Test-Team 			- GVAD, Talo, Niclas
Modellierung, Animationen 	- cdpkobra
Modellaktualiesierungen			- Soulfreak
Cockpit						          - Tolis / cdpkobra
Modell crewladder					  - TOMs Modelling in Motion - www.youtube.com/c/tomgrigat
Cockpit Textur					    - GLOBAL HAWK + VB6
RoughMet Dateien 					  - cdpkobra
VSN_F104G_psd_template		  - file404
VSN_F104S_psd_template			- file404
JaboG 32 Skin					      - file404
4 Stormo Skin					      - file404
Liveris						          - by jocko417
Liveris						          - by Soulfreak
Icons 						          - Ozone1
Theme						            - Yogi
Musik						            - Music by ComaStudio from Pixabay
ASPIDE-Missile Modell+Text.	- erworben und lizensiert über TurboSquid
ASPIDE-Missile FM/System		- Marco1985

Wen ich jemanden vergessen habe, bitte bei mir melden und ich trage es ein.


Das 3D-Modell des F-104G Starfighter basiert auf 3D-Daten von file404, die über Turbosquid erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104S Starfighter basiert auf 3D-Daten von file404, die über Turbosquid erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104 Starfighter Cockpit basiert auf 3D-Daten von Tolis die erworben und als Referenz in der Modellierung verwendet wurde.

Das 3D-Modell des F-104 crewladder basiert auf 3D-Daten von TOMs Modelling in Motion die erworben und als Referenz in der Modellierung verwendet wurde.

Der Quellcode des EFM steht unter der im dortigen Unterordner eingebrachten Lizenz. Die Weiterverwendung und Verbreitung des Quellcodes unterliegt den dort abgedruckten Lizenzbestimmungen.
Der Quellcode ist zum download verfügbar im F-104G Discord oder per Kontaktnachricht an PeeJott über das LockOn-Forum.



KONTAKTDATEN
************

cdpkobra
lockonforum.de
https://lockonforum.de/user/711-cdpkobra/#sitemap_cms

ED Forum:
https://forums.eagle.ru/member.php?u=88910
