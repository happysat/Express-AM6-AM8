# Express AM8

Express AM8 ist ein russischer geostationärer Kommunikationssatellit.

<img src="/img/Express-AM8.jpg" alt="" width="304" height="178">

Seine Sendeinhalte umfassen eine Reihe von umstrittenen <a href="https://rumble.com/v241fl2-play-with-sat-stuff.html">russischen</a>, syrischen und iranischen (Nachrichten-)Kanälen.<br>
die aufgrund von Sanktionen gegen Russland (alles) und Iran (Press TV) von den EU-Verteilern/Anbietern nicht ausgestrahlt werden dürfen.<br>

 ## Appendix

- [ 1.1 Satellitenbeschreibung ](https://github.com/happysat/Express-AM8/blob/main/README.md#satellite-description)
- [ 1.2 Dish und LNB ](https://github.com/happysat/Express-AM8/blob/main/README.md#dish-and-lnb)
- [ 1.3 Footprint ](https://github.com/happysat/Express-AM8/blob/main/README.md#footprint)
- [ 1.4 Dish Align to Express AM8 ](https://github.com/happysat/Express-AM8/blob/main/README.md#dish-align-to-express-am8)
- [ 1.5 Transponder und Frequenzen ](https://github.com/happysat/Express-AM8/blob/main/README.md#telemetry-transponders-and-beacon-frequencies)
- [ 1.6 T2-MI Technologie ](https://github.com/happysat/Express-AM8/blob/main/README.md#t2-mi-technology)
- [ 1.7 Satellitenempfänger ](https://github.com/happysat/Express-AM8/blob/main/README.md#satellite-receivers)
- [ 1.8 DVB-S Karten Software ](https://github.com/happysat/Express-AM8/blob/main/README.md#dvb-s-card-software)
- [ 1.9 Codecs, Player, Streaming Software ](https://github.com/happysat/Express-AM8/blob/main/README.md#codecs-players-streaming-software)
- [ 2.0 Elektronischer Programmführer XMLTV](https://github.com/happysat/Express-AM8/blob/main/README.md#electronic-program-guide-xmltv)
- [ 2.1 Nachrichten und Updates ](https://github.com/happysat/Express-AM8/blob/main/README.md#news-and-updates)
- [ 2.2 Haftungsausschluss ](https://github.com/happysat/Express-AM8/blob/main/README.md#disclaimer)

## Satellitenbeschreibung

Betrieben und im Besitz von RSCC (Russian Satellite Communications Company) von einer Orbitalposition auf 14° Grad West.<br>
<a href="https://www.n2yo.com/satellite/?s=40895#results">Express-AM8</a> wird hochwertige Festnetz- und Mobilkommunikationsdienste anbieten.<br>

sowie Rundfunkdienste für digitales Fernsehen und Radio, Datenübertragung,
Hochgeschwindigkeits-Internetzugang und sichere Regierungskommunikation.<br>

<img src="/img/АМ8.jpg" alt="" width="304" height="178">

<a href="https://orbit.ing-now.com/satellite/40895/2015-048a/express-am8/">Express-AM8</a> (Norad:40895 2015-048A) wurde am 14. September 2015 von einer Proton M-Trägerrakete in die Umlaufbahn gebracht.<br>
Thales Alenia Space baute die Express-AM8-Nutzlast, und ISS Reshetnev konstruierte den Satellitenbus, der auf der Ekspress-1000NTB-Plattform basiert.<br>
Der Satellit hat eine Masse von 2.100 kg (4.600 lb), liefert 5.9 Kilowatt für seine Nutzlast und eine geplante Betriebsdauer von 15 Jahren.<br>

Es sollte berücksichtigt werden, dass Express AM8 kein gewöhnlicher DTH-Hochleistungssatellit wie Astra und Hotbird ist!<br>

Express AM8 unterliegt häufigen Frequenz- und Signalstärkeänderungen.<br>
Es werden Transponder mit niedrigen Symbolraten verwendet, und es werden viele Tests durchgeführt, die von DVB-S(2) bis T2-MI reichen.<br>

Die Details und Informationen zu den Transpondern/Kanälen können sich täglich ändern.<br>
Das macht diesen Satelliten zu einem interessanten exotischen "DX"-Satelliten mit transatlantischer Abdeckung und kundenspezifischen Konfigurationen für die Ausleuchtzone.<br>

Die Satellitentransponder werden auch regelmäßig gehackt oder durch Störsignale gestört.<br>
Dies ist kein Einzelfall und ist auch bei Eutelsat Hotbird Position (und einer Reihe anderer Satelliten) passiert.<br>


## Schüssel und LNB

Für den Empfang von Express-AM8 benötigt man eine Schüssel in der Größe >75 - 85 cm.<br>
Empfohlen wird eine Größe zwischen 80 - 1,20 cm.<br>

Die bei mir verwendeten Schüsseln sind:<br>
          <br>
          <img src="img/Triax.jpg" alt="" width="267" height="187">
          &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; <img
            src="img/90cm.jpg" alt="" width="173" height="196"><br>

89CM Triax und 90CM Noname Dish.

Jede Ku-Band Satelliten-TV (DRO/PLL-basierte) LNB kann für Express AM8 verwendet werden.<br>
Ich habe verschiedene Ergebnisse mit DRO und PLL-basierte, sondern zeigt deutlich eine enorme Zunahme der Frequenzstabilität YMMV.<br>

Regelmäßige Ku-Band Satelliten-TV LNB (DRO) leiden unter Drift in der Frequenz macht es schwieriger, einen stabilen Empfang für die niedrigen Symbolrate Signale zu halten.<br>
Wegen der äußeren Bedingungen (Temperaturschwankungen, Sonne, Wolken, Wind ect).<br>

In Gebrauch auf meinem Setup sind:<br>

<img src="img/ultra.jpg" alt="" width="161" height="94"><br>

Invertro Ultra Black LNB (DRO Altes Modell mit längerem Hals).<br>

<img src="img/twin.jpg" alt="" width="185" height="185"><br>

Inverto Twin (PLL) LNB.<br>

## Footprint

Express AM8 trägt 12 Ku-Band Transponder mit drei Footprints:

<img src="img/express-am8-ku-band-fix1.jpg" alt="" width="567" height="405">

Europa/Mittlerer Osten Fixed 1

<img src="img/express-am8-ku-band-fix2.jpg" alt="" width="564" height="533">

Afrika/Mittlerer Osten Fixed 2.<br>
Und Lateinamerika/Ostküste Nordamerikas Fix 3.<br>

24 C-Band-Transponder mit Abdeckung von zwei Footprints:

Europa, Afrika und der Nahe Osten sowie Lateinamerika und die Ostküste Nordamerikas.<br>
Und die Nutzlast hat zwei L-Band-Transponder.<br>

## Dish align to Express-AM8

Es gibt mehrere Möglichkeiten, Express-AM8 am Himmel zu finden:

<a href="https://www.dishpointer.com" target="_blank">Dishpointer hat eine gute Website und eine Android-App.</a>

Geben Sie den Standort der Stadt ein und wählen Sie Express-AM8, um alle Details zu sehen.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=MNqsqvnrJbI
" target="_blank"><img src="http://img.youtube.com/vi/MNqsqvnrJbI/0.jpg"
alt="LNB Skew" width="240" height="180" border="10" /></a>

Beachten Sie die Skew-Einstellungen des LNB!<br>
Auf der Website von Dish Pointer sind die Skew-Werte für Express AM8 unter dem Bild des gewählten Standorts aufgeführt.<br>

Oder das Programm <a href="http://www.al-soft.com/saa/satinfo.shtml" target="_blank">Satellite Antenna Alignment 4.0</a><br>
für die Dish-Ausrichtung und viele weitere Optionen.<br>

Beispiele für den Express AM8-Empfang von Videos:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=wlJQ2GOm05I
" target="_blank"><img src="http://img.youtube.com/vi/wlJQ2GOm05I/0.jpg"
alt="Empfang mit einer Schüssel im Haus." width="240" height="180" border="10" /></a>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
<a href="http://www.youtube.com/watch?feature=player_embedded&v=wH6MfeTWfuo
" target="_blank"><img src="http://img.youtube.com/vi/wH6MfeTWfuo/0.jpg"
alt="RT" width="240" height="180" border="10" /></a>


## Telemetrie, Transponder und Bakenfrequenzen.

<a href="http://www.romantis.com/wp-content/uploads/2017/01/Romantis_AM8.pdf" target="_blank"><img src="img/freq-plan.jpg" alt="" width="741" height="645" border="0"></a>

Telemetrie und Bakenfrequenzen:<br>
<a href="http://frequencyplansatellites.altervista.org/Beacon-Telemetry_Atlantic/Express_AM8.html" target="_blank">3405,10 R (Global oder Omni) / 3850,00 R
(Global) / 3850,50 L (Global) / 11199,50 R (Global).</a><br>
<br>
<br>
[Up2date Express AM8 Transponder.ini file](https://github.com/happysat/Express-AM8/blob/main/3460.ini)<br>
<br>
<br>
[![Express AM8 Transponder Index](https://www.lyngsat.com/images/lyngsat_210x48.gif)](https://www.lyngsat.com/Express-AM8.html)
<br>
Lyngsat Transponder Index<br>
<br>
[![Express AM8 Transponder Index](https://en.kingofsat.net/kingofsat.gif)](https://en.kingofsat.net/pos-14W.php)
<br>
KingOfSat Transponder Index<br>

## T2-MI Technologie

T2-MI (T2 Modulator Interface) ist eine Methode zur Verkapselung eines Satellitensignals in einen MPEG TS Transportstrom.<br>
Vereinfacht ausgedrückt, werden mit Hilfe der T2Mi-Schnittstelle Programmpakete im DVB-T2-Standard vom Satelliten zu Basisstationen
 zur Weiterverteilung an T2-Türmeübertragen, <br>
die dann terrestrisches Digitalfernsehen für Fernseher oder DVB-T2-Empfänger ausstrahlen.<br>&nbsp;<br>
Das heißt, die Programmpakete in T2MI waren ursprünglich nicht für den Empfang durch heimische Satellitenempfänger gedacht.<br>
Aber mit der Entwicklung von Prozessoren für Satellitenreceiver, die sie verarbeiten können, wurde es möglich, diese TV-Kanäle zu Hause auf einem normalen Satellitenreceiver zu empfangen.<br>

<img src="img/T2-MI_2.jpg" alt="" width="640" height="440"><br>

Express AM8 verfügt über einige T2-MI-Transponder.<br>

<img src="img/T2-MI.jpg" alt="" width="508" height="306"><br>

Ausstrahlung von Kanälen auf DVB-T2-Multiplexen in der Ukraine.

## Satellitenempfänger

Nun, es gibt eine große Auswahl in diesem Bereich, es hängt ein wenig davon ab, was Sie sehen wollen.<br>

<img src="img/1-0-1-1-14-1-D842-D76-0-0-0.jpg" alt="" width="640" height="360"><br>

Vieles kann man schon mit einem normalen HD-Receiver sehen und es muss nicht der neueste Stand der Technik sein.<br>
Um die T2-MI-Multiplexe zu zeigen, braucht man natürlich einen Receiver der neuen Generation oder eine TBS-DVB-S-Karte ist empfehlenswert.<br>

Natürlich braucht man für die T2-MI Multiplexe einen Receiver der neuesten Generation oder eine <a href="https://www.tbsdtv.com/">TBS DVB-S Karte</a> wird empfohlen.<br>

Ci, Softcams oder Smartcards sind nicht notwendig, da alles Free To Air ausgestrahlt wird.<br>
Dies kann sich für die T2-MI Multiplexe in Zukunft ändern.<br>

Die in meinem Setup verwendeten Receiver sind:<br>

Dreambox 800se <a href="https://github.com/jack2015/openpli-dreambox-oe-core" target="_blank">OpenPLI 12.2</a><br>
VuSolo2 <a href="http://images.mynonpublic.com/openatv/7.1/index.php?open=vusolo" target="_blank">Open-ATV</a><br>
<a href="https://www.tbsdtv.com/" target="_blank">TBS Q-Box2</a>.<br>

## DVB-S-Kartensoftware

Es gibt eine große Auswahl an (kostenloser) Software für die DVB-S-Karten.<br>
Sie reicht von TV-Anwendungsbetrachtern bis hin zu Stream-Analysatoren.<br>

<a href="https://www.altx.ro/projects/altdvb/" target="_blank">AltDVB</a>
ist eine kostenlose Software, um digitales Fernsehen auf dem Windows-PC mit einem speziellen DVB-Hardware-Gerät zu sehen.<br>
Sie unterstützt die Standards DVB-S/S2 und T2-MI,<br>
Picture-in-Picture
(PIP), LAN-Streaming und viele andere Optionen und Funktionen.<br>

<img src="img/AltDVB.jpg" alt="" width="638" height="405"><br>

<a href="http://www.smartdvb.net/tempsite/index.html" target="_blank">SmartDVB</a>
ist eine kostenlose Digital-TV-Anwendung für Satelliten-TV-Karten. <br>
Sie unterstützt die Standards DVB-S/S2 und T2-MI.<br>
XMLTV-Importoption für EPG, Streaming, PIP und andere Optionen und Funktionen.<br>

<img src="img/smartdvb.jpg" alt="" width="635" height="438"><br>

<a href="https://sourceforge.net/projects/crazyscan/" target="_blank">Crazyscan</a>, <a href="http://ebspro.net/overview/" target="_blank">EBSPro</a> und <a
href="https://www.satellitescommunity.de/forum/index.php?thread/2005-iqmonitor-only-files/&amp;postID=45835#post45835" target="_blank">IQ Monitor</a> - Kostenlose Analysetools für Satelliten-DVB-Tuner zur Anzeige von Details und Infos zu Stream-Infos, <br>
Blind Scanning, SignalInfo, Konstellationen und vielen weiteren Optionen.<br>

<img src="img/Bild.jpg" alt="" width="493" height="579"><br>

## Codecs, Player, Streaming Software

<img src="img/demoneditor.jpg" alt="" width="611" height="348"><br>
<a href="https://github.com/DYefremov/DemonEditor" target="_blank">DemonEditor</a><br>

Enigma2 Kanal- und Satellitenlisten-Editor für Windows und Linux.<br>

Hauptmerkmale des Programms:<br>
Bearbeiten von Bouquets, Kanälen, Satelliten, Import/Backup-Funktion, Unterstützung von Picons.<br>
Export von Bouquets mit IPTV-Diensten in m3u.<br>

Zuweisung von EPG aus DVB oder XML für IPTV-Dienste (nur Enigma2).<br>
Abspielen von IPTV oder anderen Streams direkt aus der Bouquetliste.<br>
Möglichkeit, EPG einzusehen und Timer zu verwalten (über HTTP API).<br>

<img src="img/mpv.jpg" alt="" width="641" height="384"><br>
<a href="https://mpv.io/">Mpv</a>
Freier, quelloffener und plattformübergreifender Media Player.<br>

<a href="https://github.com/Nevcairiel/LAVFilters/releases">LAV-Filter</a> sind eine Reihe von DirectShow-Filtern, die auf den Bibliotheken libavformat und libavcodec aus dem ffmpeg-Projekt basieren.<br>

<img src="img/LAV.jpg" alt="" width="645" height="575"><br>

Damit können Sie praktisch jedes Format in einem DirectShow-Player abspielen.<br>

<a href="http://madvr.com/">madVR</a> ist ein DirectShow-Video-Renderer, der von Hunderttausenden von Heimkino-Enthusiasten auf der ganzen Welt verwendet wird.<br>
Entwickelt als kompromissloser Ansatz, liefert madVR die ultimative Videowiedergabequalität, auf die kein Enthusiast verzichten sollte.<br>

 ## Electronic Program Guide XMLTV

TV-Kanäle auf Express AM8 senden keine Electronic Program Guide Daten.<br>
Es ist möglich, EPG Daten im XMLTV Format selbst zu importieren.<br>

Die enigma2 basierten Receiver haben das rytec Plugin in ihrem Image Feed zum Importieren von EPG Daten.<br>

<img src="img/xmltv.jpg" alt="" width="694" height="498"><br>

DVB-S Kartensoftware einschließlich Smartdvb kann XMLTV importieren, so dass ein epg-Guide für die TV-Kanäle von Express AM8 zu sehen ist.<br>

<img src="img/epg3.jpg" alt="" width="694" height="498"><br>

Auch in den separaten Guides

<img src="img/epg.jpg" alt="" width="694" height="498"><br>

<img src="img/epg2.jpg" alt="" width="694" height="498"><br>


Download 6 Tage XMLTV EPG für:<br>

[RT Deutschland](https://github.com/happysat/Express-AM8/blob/main/rt_de.xmltv)<br>

[RT Int, Rossia-24, NTV MIR, 1TVRUS Europe, POBEDA int, RTR-Planeta Evropa und Belarus24 HD.](https://github.com/happysat/Express-AM8/blob/main/rt.xmltv)<br>


## News und Updates

26/27 Januar<br>

<img src="img/RT_Int.jpg" alt="" width="542" height="299"><br>

Störsignal auf RT und fast allen anderen russischen Transpondern.<br>
Auf einigen Transpondern sind die Signalpegel höher als sonst.

25. Januar<br>

TV-Übertragungen im Südwesten Russlands wurden kurzzeitig durch eine Ansprache des ukrainischen Präsidenten gestört, die Störung betraf Satellitenübertragungen, so der Pressedienst der Regionalregierung. <br>
Die Betreiber mussten das Signal von einem Ersatzsatelliten umleiten.<br>

<a href="https://thepressunited.com/updates/zelensky-appears-on-russian-tv/" target="_blank">Zelensky erscheint im russischen Fernsehen</a>.<br>

24. Januar<br>

Pobeda wieder als "POBEDA int" auf 11653 V 4880 2/3.<br>

<img src="img/POBEDA.jpg" alt="" width="518" height="274"><br>

23. Januar<br>

IRIB - JAMEJAM1 HD, SAHAR BALKAN/AZARI, PRESS TV HD, HISPAN TV, iFILM ENGLISH, ALALAM HD - 11670 H 16596.

21. Januar<br>

PRESS TV HD - 11498 H Gone.

20. Januar<br>

Syria, Syria Sport 24, Syria CH1, Syria News, Drama 24, Sakaker - 11690 H 12110.

<img src="img/Syrian.jpg" alt="" width="515" height="356"><br>

PRESS TV HD - 11498 H 6938.<br>

<img src="img/PRESSTV.jpg" alt="" width="511" height="288"><br>

18. Januar<br>

1TVRUS sendet jetzt in 2/3. <br>
Pobeda wird abgeschaltet.<br>
Viele Unterbrechungen auf RT Transponder. <br>

<img src="img/rtde.jpg" alt="" width="525" height="292"><br>

<img src="img/jam.jpg" alt="" width="500" height="31"><br>

17. Januar<br>

Syrische Transponder löschen 11600 V.<br>

5. Januar 2023<br>

Express AM8 Transponder 11647V wurde heute um 18:30 Uhr vom ukrainischen Ministerium für strategische Kommunikation gehackt.<br>
Eine Neujahrsansprache des ukrainischen Präsidenten V. Selensky wurde kurzzeitig in ukrainischer Sprache auf allen Programmplätzen des T2-MI-Transponders ausgestrahlt.<br>

<img src="img/1_0_1_B_5_0_D84AD7F_0_0_0_202301.jpg" alt="" width="516" height="289"><br>

## Disclaimer

Diese Website ist nur für Bildungszwecke gedacht.<br>
Die Europäische Union bezeichnet alternative Nachrichtenquellen auf diesem Satelliten als Propaganda.<br>

Einwohner der Europäischen Union dürfen diese Inhalte ansehen, aber nicht live verbreiten.<br>
Dieser Satellit und die Kanäle, die seine Inhalte übertragen, werden von RSCC (Russian Satellite Communications Company) kontrolliert.

## Autoren

- [Express AM8 von Happysat](https://github.com/happysat/Express-AM8
