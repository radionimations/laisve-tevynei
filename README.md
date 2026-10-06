# Laisvė Tėvynei

*Freedom for the Homeland.* A grand strategy game in the style of Hearts of Iron IV and Europa
Universalis IV about Lithuania under Russian rule, 1800 to 1924, with procedural history after 1924.
The map covers Eastern Europe from the Baltic to the Black Sea. Its states are the real districts of the
time: the Russian Empire's uezds (1897) and Prussia's Kreise (1900) around Lithuania, governorates and
Regierungsbezirke further away, cut along every border that held between 1800 and 1925, and divided into
some 4,600 provinces (about 280 km2 each around Lithuania). Borders change with history (the Duchy of
Warsaw, Congress Poland, the Balkan wars, the Great War, the new states of 1918) unless you change them.

Play it online: https://radionimations.github.io/laisve-tevynei/

The game is one HTML file (`index.html` on the site); it needs an internet connection for three.js
(jsDelivr CDN) and Google Fonts. Its source is kept in a private repository, where
`python tools/build_single.py` builds the file into `dist/LaisveTevynei.html` and `dist/github/`.

## Playing

- Drag to pan, mouse wheel to zoom, WASD to move. Space pauses; keys 1 to 5 set the speed.
- Click a district for its window and actions; click the flag for the politics screen.
- F national focus, H Cities of the Nation, J decisions, P diplomacy, G leadership, R army, L ledger.
- Under occupation: raise awareness, literacy, networks and tension, keep police suspicion low,
  then launch a rising from the ignition points you choose.
- As a state: recruit in the army panel, select units by their counters, right-click a province
  to move or attack. Battles are fought province by province.
- Saves stay in the browser (Menu, Save); Export gives a save code you can keep anywhere.

## Sources and licences

- Elevation: AWS Terrain Tiles (Terrarium), derived from SRTM, ETOPO1 and other public sources.
- Land cover: ESA WorldCover 2021 v200, (c) ESA WorldCover project, licensed CC BY 4.0
  (https://esa-worldcover.org). Modified: reclassified and resampled for the game map.
- Districts (uezds) of the Russian Empire in 1897: RISTAT, Electronic Repository of Russian Historical Statistics
  (Kessler, Gijs and Andrei Markevich, https://ristat.org/, Version I (2020)), released under CC0 with that citation.
- Kreise, districts and counties of Prussia, Austria-Hungary and Moldavia around 1900, and the dated country
  borders used for every change of owner from 1800 to 1925: OpenHistoricalMap (https://www.openhistoricalmap.org),
  (c) OpenHistoricalMap contributors, Open Database License (ODbL 1.0). The map data embedded in the game
  (district shapes, provinces and ownership timelines) is a derivative database and is shared under the ODbL.
- 1897 census by governorate (languages, population): Transcultural Empire GIS of the 1897 and 1926 censuses,
  heiDATA, Heidelberg University (doi:10.11588/data/10064), CC BY 4.0.
- Rivers, modern first-level regions (outside the old empires) and towns: Natural Earth (public domain).
- Matching the story's older district names to the historical districts used geoBoundaries gbOpen (CC BY 4.0)
  and CShapes 2.0 (Schvitz et al. 2022, CC BY-NC-SA 4.0) at build time.
- Names for the parts of districts cut by later borders were chosen with the help of GeoNames
  (https://www.geonames.org, CC BY 4.0) at build time; Lithuanian forms follow the Lithuanian Wikipedia.
- 3D engine: three.js r149 (MIT licence), loaded from jsDelivr.
- Fonts: Old Standard TT, Alegreya and Barlow Semi Condensed from Google Fonts (SIL Open Font Licence).
- Historical pictures and portraits: public-domain works from Wikimedia Commons, listed below.
- Ethnic make-up where the 1897 census does not reach, and all game text: written for this game.

### Event pictures
- `act_1918`: File:Signatures in 1918 Act of Independence of Lithuania.jpg, Unknown, 1918 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Signatures_in_1918_Act_of_Independence_of_Lithuania.jpg
- `armored_train`: File:Lithuanian Wars of Independence, War with Poland. Armoured train Gediminas of Lithuanian army in Kaunas, before leaving to front, 1920 08 25.jpg, Unknown, 1920-08-25 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Lithuanian_Wars_of_Independence,_War_with_Poland._Armoured_train_Gediminas_of_Lithuanian_army_in_Kaunas,_before_leaving_to_front,_1920_08_25.jpg
- `army_1919`: File:Volunteer soldiers of the Republic of Lithuania on a march, 1919.jpg, Unknown, 1919 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Volunteer_soldiers_of_the_Republic_of_Lithuania_on_a_march,_1919.jpg
- `ausra`: File:Ausra newspaper.jpg, Auszra (newspaper), Tilsit, 1884 (Public domain (PD-1996)) https://commons.wikimedia.org/wiki/File:Ausra_newspaper.jpg
- `basanavicius`: File:Jonas Basanavicius (1851-1927).jpg, Aleksandras Jurašaitis (1859-1915), 1905 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Jonas_Basanavicius_(1851-1927).jpg
- `battle`: File:Battle of Borodino on 26 August (7 September) 1812 (by Peter von Hess).jpg, Peter von Hess, 1843 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:Battle_of_Borodino_on_26_August_(7_September)_1812_(by_Peter_von_Hess).jpg
- `bermontians`: File:Pavel Bermondt-Avalov with a group of officers, c. 1919.jpg, Latvian War Museum, circa 1919 (Public domain (PD-US, PD-US-expired)) https://commons.wikimedia.org/wiki/File:Pavel_Bermondt-Avalov_with_a_group_of_officers,_c._1919.jpg
- `book_smugglers`: File:Bielinis.jpg, Boleslovas Savsenavičius / Bolesław Sawsienowicz, circa 1915 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Bielinis.jpg
- `cat_army`: File:Lithuanian Wars of Independence, War with Poland and Bermontians. Lithuanian soldiers and the armoured car Pragaras (Hell) of Lithuanian army, circa 1920s, Lithuania.jpg, Unknown, ca 1920s (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Lithuanian_Wars_of_Independence,_War_with_Poland_and_Bermontians._Lithuanian_soldiers_and_the_armoured_car_Pragaras_(Hell)_of_Lithuanian_army,_circa_1920s,_Lithuania.jpg
- `cat_books`: File:Lithuanian language book, printed in the Civil Script during the Lithuanian press ban, Vilnius, 1865.jpg, Unknown, printed by the R. M. Romm Press, 1865 (Public domain (PD-old-70-expired)) https://commons.wikimedia.org/wiki/File:Lithuanian_language_book,_printed_in_the_Civil_Script_during_the_Lithuanian_press_ban,_Vilnius,_1865.jpg
- `cat_church`: File:Stanisław Witkiewicz Procesya na Żmudzi 1878.jpg, Stanisław Witkiewicz, 1878 (Public domain (PD-old-70, PD-old)) https://commons.wikimedia.org/wiki/File:Stanis%C5%82aw_Witkiewicz_Procesya_na_%C5%BBmudzi_1878.jpg
- `cat_city`: File:Eugeniusz Kazimirowski - Panorama Wilna 1916.jpg, Eugeniusz Kazimirowski, 1916 (Public domain (PD-Art (PD-old-auto-expired), PD-old-80-expired)) https://commons.wikimedia.org/wiki/File:Eugeniusz_Kazimirowski_-_Panorama_Wilna_1916.jpg
- `cat_conspiracy`: File:Przysiega - Grottger (5579125).jpg, Artur Grottger, 1888 (Public domain (PD-old-100-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Przysiega_-_Grottger_(5579125).jpg
- `cat_diplomacy`: File:Congress of Berlin, 13 July 1878, by Anton von Werner.jpg, Anton von Werner, 1892 (Public domain (PD-old-100)) https://commons.wikimedia.org/wiki/File:Congress_of_Berlin,_13_July_1878,_by_Anton_von_Werner.jpg
- `cat_disaster`: File:Корабль помощи.jpg, Ivan Aivazovsky, 1890s (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:%D0%9A%D0%BE%D1%80%D0%B0%D0%B1%D0%BB%D1%8C_%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D0%B8.jpg
- `cat_industry`: File:Adolph Menzel - Das Eisenwalzwerk - The Iron-Rolling Mill - 1872-1875.JPG, Adolph von Menzel, 1872-1875 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:Adolph_Menzel_-_Das_Eisenwalzwerk_-_The_Iron-Rolling_Mill_-_1872-1875.JPG
- `cat_politics`: File:Demonstrators congratulate the assembled Constituent Assembly of Lithuania (Kaunas, 1920).jpg, Unknown, 1920-05-15 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Demonstrators_congratulate_the_assembled_Constituent_Assembly_of_Lithuania_(Kaunas,_1920).jpg
- `cat_portrait`: File:Rusiecki-Litwinka z wierzbami.jpg, Kanuty Rusiecki, 1847 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired), PD-Art, PD-old)) https://commons.wikimedia.org/wiki/File:Rusiecki-Litwinka_z_wierzbami.jpg
- `cat_repression`: File:Malczewski Prisoners.jpg, Jacek Malczewski, 1883 (Public domain (PD-Art (PD-old-auto-expired), PD-old-95-expired)) https://commons.wikimedia.org/wiki/File:Malczewski_Prisoners.jpg
- `cat_school`: File:Bogdanov-Belsky Ustny Schet (Tretyakov).jpg, Nikolay Bogdanov-Belsky, 1895 (Public domain (PD-Art (PD-old-auto-expired), PD-old-80-expired)) https://commons.wikimedia.org/wiki/File:Bogdanov-Belsky_Ustny_Schet_(Tretyakov).jpg
- `cat_ship`: File:Raddampfer Liutas.jpg, Unknown, about 1923 (Public domain (PD-US-expired)) https://commons.wikimedia.org/wiki/File:Raddampfer_Liutas.jpg
- `cat_uprising`: File:Emilia Plater w potyczce pod Szawlami.jpg, Wojciech Kossak, 1904 (Public domain (PD-Art (PD-old-auto-expired), PD-old-80-expired)) https://commons.wikimedia.org/wiki/File:Emilia_Plater_w_potyczce_pod_Szawlami.jpg
- `cat_village`: File:Old Vepriai.jpg, Unknown, circa 1898 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Old_Vepriai.jpg
- `cat_war`: File:George Jones (1786-1869) - Battle of Borodino - N00391 - National Gallery.jpg, George Jones, 1829 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:George_Jones_(1786-1869)_-_Battle_of_Borodino_-_N00391_-_National_Gallery.jpg
- `cavalry`: File:Battle of Grochów 1831.JPG, Bogdan Willewalde, circa 1850 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:Battle_of_Groch%C3%B3w_1831.JPG
- `church`: File:Album Wilenskie. 1845-1875 (5552596).jpg, Philippe Benoist (lithograph), figures by Adolphe Bayot; published by J. K. Wilczyński, 1845-1875 (Public domain (PD-anon-expired)) https://commons.wikimedia.org/wiki/File:Album_Wilenskie._1845-1875_(5552596).jpg
- `constitution`: File:One of the first meetings of the Constituent Assembly of Lithuania in the Kaunas City Theatre in 1920.jpg, Unknown, 1920 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:One_of_the_first_meetings_of_the_Constituent_Assembly_of_Lithuania_in_the_Kaunas_City_Theatre_in_1920.jpg
- `cross_crafting`: File:Mikalojus Konstantinas Ciurlionis - WAYSIDE CROSSES OF ZEMAITIJA - 1909.jpg, Mikalojus Konstantinas Čiurlionis, 1909 (Public domain (PD-old-100, PD-old)) https://commons.wikimedia.org/wiki/File:Mikalojus_Konstantinas_Ciurlionis_-_WAYSIDE_CROSSES_OF_ZEMAITIJA_-_1909.jpg
- `daukantas`: File:Simonas Daukantas.png, Jonas Zenkevičius / Jan Zienkiewicz (1825-1888), circa 1850 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired), PD-Art, PD-old)) https://commons.wikimedia.org/wiki/File:Simonas_Daukantas.png
- `diplomacy`: File:Congres de vienne.png, after Jean-Baptiste Isabey, about 1815-1819 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Congres_de_vienne.png
- `duma`: File:Opening of Duma.jpg, C. E. de Hahn & Co., Tsarskoye Selo, 10 May 1906 (Public domain (PD-Russia-expired)) https://commons.wikimedia.org/wiki/File:Opening_of_Duma.jpg
- `emigrants`: File:Alfred Stieglitz - The Steerage - Google Art Project.jpg, Alfred Stieglitz, 1907 (Public domain (PD-Art (PD-old-auto-expired), PD-old-75-expired)) https://commons.wikimedia.org/wiki/File:Alfred_Stieglitz_-_The_Steerage_-_Google_Art_Project.jpg
- `famine`: File:Айвазовский - Раздача продовольствия.jpg, Ivan Aivazovsky, 1890s (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:%D0%90%D0%B9%D0%B2%D0%B0%D0%B7%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B9_-_%D0%A0%D0%B0%D0%B7%D0%B4%D0%B0%D1%87%D0%B0_%D0%BF%D1%80%D0%BE%D0%B4%D0%BE%D0%B2%D0%BE%D0%BB%D1%8C%D1%81%D1%82%D0%B2%D0%B8%D1%8F.jpg
- `fire`: File:Kauno GS 1.jpg, Unknown, circa 1915 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Kauno_GS_1.jpg
- `forest`: File:Ferdynand Ruszczyc - Forest rivulet - MP 454 - National Museum in Warsaw.jpg, Ferdynand Ruszczyc, 1898-1900 (Public domain (PD-Art (PD-old-auto-expired), PD-old-80-expired)) https://commons.wikimedia.org/wiki/File:Ferdynand_Ruszczyc_-_Forest_rivulet_-_MP_454_-_National_Museum_in_Warsaw.jpg
- `gallows`: File:Vilnia, Muravyov-viešalnik. Вільня, Мураўёў-вешальнік (1898).jpg, Unknown, 1898 (Public domain (PD-old-70-expired)) https://commons.wikimedia.org/wiki/File:Vilnia,_Muravyov-vie%C5%A1alnik._%D0%92%D1%96%D0%BB%D1%8C%D0%BD%D1%8F,_%D0%9C%D1%83%D1%80%D0%B0%D1%9E%D1%91%D1%9E-%D0%B2%D0%B5%D1%88%D0%B0%D0%BB%D1%8C%D0%BD%D1%96%D0%BA_(1898).jpg
- `german_army`: File:Deutsche Infanterie rückt in Wilna ein.jpg, Unknown photographer; postcard published by Gebr. Hochland, Königsberg, circa 1915 (CC0 (CC0)) https://commons.wikimedia.org/wiki/File:Deutsche_Infanterie_r%C3%BCckt_in_Wilna_ein.jpg
- `grande_armee`: File:French retreat in 1812 by Pryanishnikov.jpg, Illarion Mikhailovich Pryanishnikov, 1874 (Public domain (PD-old-100-expired, PD-Art (PD-old-100-expired))) https://commons.wikimedia.org/wiki/File:French_retreat_in_1812_by_Pryanishnikov.jpg
- `kalinauskas`: File:Kastuś Kalinoŭski. Кастусь Каліноўскі (G. Bonoldi, 1862-63).jpg, Giuseppe Achille Bonoldi, between 1862 and 1863 (Public domain (PD-old-100, PD-old)) https://commons.wikimedia.org/wiki/File:Kastu%C5%9B_Kalino%C5%ADski._%D0%9A%D0%B0%D1%81%D1%82%D1%83%D1%81%D1%8C_%D0%9A%D0%B0%D0%BB%D1%96%D0%BD%D0%BE%D1%9E%D1%81%D0%BA%D1%96_(G._Bonoldi,_1862-63).jpg
- `kaunas_old`: File:20071016221438 04 SenamiesTio-vaizdas Orda-.jpg, Napoleon Orda (1807-1883), 1875 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:20071016221438_04_SenamiesTio-vaizdas_Orda-.jpg
- `klaipeda_1923`: File:Klaipeda Revolt 1923 - Lithuanian rebels.jpg, Unknown, 1923-01 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Klaipeda_Revolt_1923_-_Lithuanian_rebels.jpg
- `kraziai`: File:Lietuviszkas albumas - Lithuanian album 1898 (19163245).jpg, Unknown artist; Lietuviszkas albumas, ed. A. Milukas, Shenandoah, Pa., 1898 (Public domain (PD-anon-expired)) https://commons.wikimedia.org/wiki/File:Lietuviszkas_albumas_-_Lithuanian_album_1898_(19163245).jpg
- `kudirka`: File:Vincas Kudirka. Portretas.LG3316.jpg, Unknown, 1890s (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Vincas_Kudirka._Portretas.LG3316.jpg
- `litas`: File:Banknote of 1 Lithuanian litas with Vytis (Waykimas), Columns of Gediminas and Double Cross of the Jagiellonians, 1922.jpg, Adomas Varnas (design), Bank of Lithuania, 1922 (Public domain (PD-LT-exempt (banknotes))) https://commons.wikimedia.org/wiki/File:Banknote_of_1_Lithuanian_litas_with_Vytis_(Waykimas),_Columns_of_Gediminas_and_Double_Cross_of_the_Jagiellonians,_1922.jpg
- `manor`: File:Siesikai manor in 19th c.(2).jpg, Napoleon Orda, 19th century (Public domain (PD-old-100)) https://commons.wikimedia.org/wiki/File:Siesikai_manor_in_19th_c.(2).jpg
- `market`: File:Stanisław Bohusz-Siestrzeńcewicz - Rynek (1896).jpg, Stanisław Bohusz-Siestrzeńcewicz, 1896 (Public domain (PD-Art (PD-old-auto-expired), PD-old-95-expired)) https://commons.wikimedia.org/wiki/File:Stanis%C5%82aw_Bohusz-Siestrze%C5%84cewicz_-_Rynek_(1896).jpg
- `mickiewicz`: File:Wańkowicz Adam Mickiewicz (detail).jpg, Walenty Wańkowicz, 1828 (Public domain (PD-old-100-expired, PD-Art (PD-old-100-expired))) https://commons.wikimedia.org/wiki/File:Wa%C5%84kowicz_Adam_Mickiewicz_(detail).jpg
- `muravyov`: File:Муравьёв-Виленский литография.jpg, Smirnov (lithographer), St Petersburg, 1865 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:%D0%9C%D1%83%D1%80%D0%B0%D0%B2%D1%8C%D1%91%D0%B2-%D0%92%D0%B8%D0%BB%D0%B5%D0%BD%D1%81%D0%BA%D0%B8%D0%B9_%D0%BB%D0%B8%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D1%8F.jpg
- `napoleon`: File:Crossing the Neman in Russia 1812 by Clark.jpg, John Heaveside Clark and Matthew Dubourg, 1816 (Public domain (PD-old-100-expired, PD-Art (PD-old-100-expired))) https://commons.wikimedia.org/wiki/File:Crossing_the_Neman_in_Russia_1812_by_Clark.jpg
- `ober_ost`: File:Stab Oberost.jpg, Unknown, 1915 (printed 19 August 1915) (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Stab_Oberost.jpg
- `oginski`: File:Michał Kleafas Aginski. Міхал Клеафас Агінскі (F. Fabre, 1805).jpg, François-Xavier Fabre, 1805 or 1806 (Public domain (PD-old-100, PD-old)) https://commons.wikimedia.org/wiki/File:Micha%C5%82_Kleafas_Aginski._%D0%9C%D1%96%D1%85%D0%B0%D0%BB_%D0%9A%D0%BB%D0%B5%D0%B0%D1%84%D0%B0%D1%81_%D0%90%D0%B3%D1%96%D0%BD%D1%81%D0%BA%D1%96_(F._Fabre,_1805).jpg
- `partisans`: File:Malecki Insurgent patrol.jpg, Władysław Malecki, 1883 (Public domain (PD-old-100-expired, PD-Art (PD-old-100-expired))) https://commons.wikimedia.org/wiki/File:Malecki_Insurgent_patrol.jpg
- `peasants`: File:Family of Lithuanian book carrier Tomas Paliulis in Vabalninkas, 1895, Lithuania.jpg, Unknown, 1895 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Family_of_Lithuanian_book_carrier_Tomas_Paliulis_in_Vabalninkas,_1895,_Lithuania.jpg
- `philomaths`: File:PhilomathesPhilarethes.jpg, Unknown engraver, 19th century (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:PhilomathesPhilarethes.jpg
- `plater`: File:Emila Plater conducting Polish scythemen in 1831.jpg, Jan Rosen, 19th century (Public domain (PD-Art (PD-old-auto-expired), PD-old-80-expired)) https://commons.wikimedia.org/wiki/File:Emila_Plater_conducting_Polish_scythemen_in_1831.jpg
- `polish_army`: File:Wilno 1919 artyleria.jpg, Unknown, 1919-04 (Public domain (PD-Poland, PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Wilno_1919_artyleria.jpg
- `press`: File:Ramage Press2'8'23.jpg, Unknown engraver (in The Memorial History of Boston, 1880), 1880 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Ramage_Press2%278%2723.jpg
- `red_army`: File:Bolseviku 7 pulko kariai.jpg, Unknown, 1919 (Public domain (PD-old-70, PD-old)) https://commons.wikimedia.org/wiki/File:Bolseviku_7_pulko_kariai.jpg
- `russian_revolution`: File:Soldiers demonstration.February 1917.jpg, Unknown, 1917-02 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Soldiers_demonstration.February_1917.jpg
- `school_secret`: File:Daraktoriai - underground Lithuanian teachers in occupied Lithuania, Berželiai manor, 1903.webp, Unknown, 1903 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Daraktoriai_-_underground_Lithuanian_teachers_in_occupied_Lithuania,_Ber%C5%BEeliai_manor,_1903.webp
- `seimas_1905`: File:Great Seimas agenda.jpg, Organizational Committee of the Great Seimas of Vilnius, 1905 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Great_Seimas_agenda.jpg
- `ship`: File:Kauno uostas 3.jpg, Unknown, circa 1910 (Public domain (PD-US, PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Kauno_uostas_3.jpg
- `siberia`: File:Farewell Europe!.jpg, Aleksander Sochaczewski, 1894 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:Farewell_Europe!.jpg
- `sierakowski`: File:Zygmunt Sierakowski 1863 (31236873) (cropped).jpg, Nadar, 1863 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:Zygmunt_Sierakowski_1863_(31236873)_(cropped).jpg
- `taryba`: File:1917 lithuanian council.jpg, Unknown, 1917 (Public domain (PD-old)) https://commons.wikimedia.org/wiki/File:1917_lithuanian_council.jpg
- `tilsit`: File:Tilsitz 1807.JPG, Adolphe Roehn, 1808 (Public domain (PD-old-100-expired, PD-Art (PD-old-auto-expired))) https://commons.wikimedia.org/wiki/File:Tilsitz_1807.JPG
- `train`: File:Kaunas Railway Tunnel.jpg, Unknown, 19th century (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Kaunas_Railway_Tunnel.jpg
- `university`: File:Vilnia, Universyteckaja, Vialiki Dvor. Вільня, Унівэрсытэцкая, Вялікі Двор (P. Benoist, 1850).jpg, Philippe Benoist, Adolphe Jean-Baptiste Bayot, 1850 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Vilnia,_Universyteckaja,_Vialiki_Dvor._%D0%92%D1%96%D0%BB%D1%8C%D0%BD%D1%8F,_%D0%A3%D0%BD%D1%96%D0%B2%D1%8D%D1%80%D1%81%D1%8B%D1%82%D1%8D%D1%86%D0%BA%D0%B0%D1%8F,_%D0%92%D1%8F%D0%BB%D1%96%D0%BA%D1%96_%D0%94%D0%B2%D0%BE%D1%80_(P._Benoist,_1850).jpg
- `uprising_1831`: File:Marcin Zaleski, Wzięcie Arsenału.jpg, Marcin Zaleski, 1831 (Public domain (PD-old-100, PD-old)) https://commons.wikimedia.org/wiki/File:Marcin_Zaleski,_Wzi%C4%99cie_Arsena%C5%82u.jpg
- `uprising_1863`: File:Kucie kos (5579011).jpg, Artur Grottger, 1888 (Public domain (PD-old-100-expired)) https://commons.wikimedia.org/wiki/File:Kucie_kos_(5579011).jpg
- `valancius`: File:Maciej Wołonczewski (cropped).jpg, Szymiel Bucher, 1867 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Maciej_Wo%C5%82onczewski_(cropped).jpg
- `varpas`: File:Varpas1889.jpg, Editor Vincas Kudirka, 1889-01 (Public domain (PD-1996)) https://commons.wikimedia.org/wiki/File:Varpas1889.jpg
- `village`: File:Lithuanian landscape. Užupis village, Anykščiai, begining of the 20th century.jpg, Unknown, ca 1920s (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Lithuanian_landscape._U%C5%BEupis_village,_Anyk%C5%A1%C4%8Diai,_begining_of_the_20th_century.jpg
- `vilnius_old`: File:Album Wilenskie. 1845-1875 (5552457) (cropped).jpg, Vasily Sadovnikov (drawing), lithographed by Dorry; published by J. K. Wilczyński, 1845-1875 (Public domain (PD-anon-expired)) https://commons.wikimedia.org/wiki/File:Album_Wilenskie._1845-1875_(5552457)_(cropped).jpg
- `volunteers`: File:Lithuanian military history. Volunteers of the Lithuanian army leave for the front. Kaunas, 1919, Lithuania.jpg, Unknown, 1919 (Public domain (PD-anon-70-EU)) https://commons.wikimedia.org/wiki/File:Lithuanian_military_history._Volunteers_of_the_Lithuanian_army_leave_for_the_front._Kaunas,_1919,_Lithuania.jpg
- `wooden_church`: File:St. Apostle Evangelist Matthew's Church in Naujamiestis, Lithuania, 1904.jpg, Adomas Daukša, 1904 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:St._Apostle_Evangelist_Matthew%27s_Church_in_Naujamiestis,_Lithuania,_1904.jpg
- `ww1_front`: File:Russian trenches LCCN2014698625.jpg, Bain News Service, publisher, 1915 (Public domain (PD-Bain, PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Russian_trenches_LCCN2014698625.jpg
- `zeligowski`: File:Lucjan Żeligowski in front of the Vilnius Cathedral following the military annexation of Vilnius from the Lithuanians, 1920.jpg, Unknown, 1920 (Public domain (PD-old-70-expired, PD-old)) https://commons.wikimedia.org/wiki/File:Lucjan_%C5%BBeligowski_in_front_of_the_Vilnius_Cathedral_following_the_military_annexation_of_Vilnius_from_the_Lithuanians,_1920.jpg

### Portraits
- `baranauskas`: File:Antanas Baranauskas in 1899 portrait (cropped).jpeg, Jan Mieczkowski photo studio in Warsaw, 1899 (CC0 cc0) https://commons.wikimedia.org/wiki/File:Antanas_Baranauskas_in_1899_portrait_(cropped).jpeg
- `basanavicius`: File:Jonas Basanavicius (1851-1927).jpg, Aleksandras Jurašaitis (1859-1915), 1905 (Public domain pd) https://commons.wikimedia.org/wiki/File:Jonas_Basanavicius_(1851-1927).jpg
- `bielinis`: File:Bielinis.jpg, Boleslovas Savsenavičius / Bolesław Sawsienowicz, circa 1915date QS:P,+1915-00-00T00:00:00 (Public domain pd) https://commons.wikimedia.org/wiki/File:Bielinis.jpg
- `bite`: File:Gabrielė Petkevičaitė-Bitė around 1935.jpeg, Rights: Maironio lietuvių literatūros muziejus / Maironis Lithuanian Literature , circa 1935date QS:P,+1935-00-00T00:00:00 (CC0 cc0) https://commons.wikimedia.org/wiki/File:Gabriel%C4%97_Petkevi%C4%8Dait%C4%97-Bit%C4%97_around_1935.jpeg
- `czartoryski`: File:Prince Czartoryski by Nadar.jpg, Nadar, 1861 (Public domain pd) https://commons.wikimedia.org/wiki/File:Prince_Czartoryski_by_Nadar.jpg
- `daukantas`: File:Simonas Daukantas.png, Jonas Zenkevičius / Jan Zienkiewicz (1825-1888), circa 1850date QS:P,+1850-00-00T00:00:00 (Public domain pd) https://commons.wikimedia.org/wiki/File:Simonas_Daukantas.png
- `galvanauskas`: File:Ernestas-Galvanauskas.jpg, unknown (added by arz), 2009-01-06 (Public domain pd) https://commons.wikimedia.org/wiki/File:Ernestas-Galvanauskas.jpg
- `galvydis`: File:GalvydisBykauskas.jpg, Adomas Kliučinskis, uploaded by Rimantas Lazdynas, 2011-05-21 (Public domain pd) https://commons.wikimedia.org/wiki/File:GalvydisBykauskas.jpg
- `giedraitis`: File:Juzef Arnulf Giedrojc. Юзэф Арнульф Гедройц (XIX).jpg, Unknown authorUnknown author, 19th centurydate QS:P,+1850-00-00T00:00: (Public domain pd) https://commons.wikimedia.org/wiki/File:Juzef_Arnulf_Giedrojc._%D0%AE%D0%B7%D1%8D%D1%84_%D0%90%D1%80%D0%BD%D1%83%D0%BB%D1%8C%D1%84_%D0%93%D0%B5%D0%B4%D1%80%D0%BE%D0%B9%D1%86_(XIX).jpg
- `gieysztor`: File:Jakub Gieysztor.PNG, Anonymous photography, 19th centurydate QS:P,+1850-00-00T00:00: (Public domain pd) https://commons.wikimedia.org/wiki/File:Jakub_Gieysztor.PNG
- `grinius`: File:Kazys Grinius.jpg, unknown (added by arz), 1926 (Public domain pd) https://commons.wikimedia.org/wiki/File:Kazys_Grinius.jpg
- `jurgutis`: File:Vladas Jurgutis.jpg, Unknown. Uploaded by Arz, photo taken in Kaunas, 1929. (Public domain pd) https://commons.wikimedia.org/wiki/File:Vladas_Jurgutis.jpg
- `kalinauskas`: File:Konstanty Kalinowski - between 1862 and 1863.jpg, Giuseppe Achille Bonoldi, between 1862 and 1863date QS:P,+1862-00- (Public domain pd) https://commons.wikimedia.org/wiki/File:Konstanty_Kalinowski_-_between_1862_and_1863.jpg
- `konarski`: File:Szymon Konarski.JPG, anonymous, before 1839date QS:P571,+1839-00-00T00:0 (Public domain pd) https://commons.wikimedia.org/wiki/File:Szymon_Konarski.JPG
- `kudirka`: File:Kudirka3.jpg, Vincas Kudirka (Public domain pd) https://commons.wikimedia.org/wiki/File:Kudirka3.jpg
- `mackevicius`: File:Antanas Mackevičius (cropped).jpeg, Unknown authorUnknown author, before 1863date QS:P,+1863-00-00T00:00:0 (CC0 cc0) https://commons.wikimedia.org/wiki/File:Antanas_Mackevi%C4%8Dius_(cropped).jpeg
- `mindaugas_ii`: File:Mindaugas II.jpg, Unknown authorUnknown author, Late 19th century (Public domain pd) https://commons.wikimedia.org/wiki/File:Mindaugas_II.jpg
- `muravyov`: File:Portrait of Muravyov-Vilensky.jpg, Unknown authorUnknown author, between 1865 and 1869date QS:P,+1865-00- (Public domain pd) https://commons.wikimedia.org/wiki/File:Portrait_of_Muravyov-Vilensky.jpg
- `oginski`: File:Michał Kleafas Aginski. Міхал Клеафас Агінскі (F. Fabre, 1805).jpg, François-Xavier Fabre, 1805 or 1806date QS:P571,+1805-00-00T00: (Public domain pd) https://commons.wikimedia.org/wiki/File:Micha%C5%82_Kleafas_Aginski._%D0%9C%D1%96%D1%85%D0%B0%D0%BB_%D0%9A%D0%BB%D0%B5%D0%B0%D1%84%D0%B0%D1%81_%D0%90%D0%B3%D1%96%D0%BD%D1%81%D0%BA%D1%96_(F._Fabre,_1805).jpg
- `pilsudski`: File:Józef Piłsudski (22-1-4) cropped.jpg, Unknown authorUnknown author, before 1935date QS:P,+1935-00-00T00:00:0 (Public domain pd) https://commons.wikimedia.org/wiki/File:J%C3%B3zef_Pi%C5%82sudski_(22-1-4)_cropped.jpg
- `plater`: File:Emilia Plater (284384).jpg, Józef Straszewicz, between 1832 and 1837date QS:P,+1832-00- (Public domain pd) https://commons.wikimedia.org/wiki/File:Emilia_Plater_(284384).jpg
- `plechavicius`: File:General Povilas Plechavicius (1890-1973).jpg, Unknown authorUnknown author, before 1940date QS:P,+1940-00-00T00:00:0 (Public domain pd) https://commons.wikimedia.org/wiki/File:General_Povilas_Plechavicius_(1890-1973).jpg
- `radziwill`: File:Dominik Hieronim Radziwiłł.PNG, Unidentified painter, 19th centurydate QS:P,+1850-00-00T00:00: (Public domain pd) https://commons.wikimedia.org/wiki/File:Dominik_Hieronim_Radziwi%C5%82%C5%82.PNG
- `romeris`: File:Mykolas Pijus Römeris.jpg, Unknown authorUnknown author, 1936 (Public domain pd) https://commons.wikimedia.org/wiki/File:Mykolas_Pijus_R%C3%B6meris.jpg
- `sierakowski`: File:Zygmunt Sierakowski 1863 (31236873) (cropped).jpg, Nadar, 1863 (Public domain pd) https://commons.wikimedia.org/wiki/File:Zygmunt_Sierakowski_1863_(31236873)_(cropped).jpg
- `slezevicius`: File:Mykolas Sleževičius.jpg, Unknown authorUnknown author, Unknown date (Public domain pd) https://commons.wikimedia.org/wiki/File:Mykolas_Sle%C5%BEevi%C4%8Dius.jpg
- `smetona`: File:Sennecke - Antanas Smetona, 1929.jpg, Robert Sennecke, 1929 (Public domain pd) https://commons.wikimedia.org/wiki/File:Sennecke_-_Antanas_Smetona,_1929.jpg
- `soltan`: File:Stanisław Sołtan szermierz.jpg, b.d., ok. 1948 (CC0 cc0) https://commons.wikimedia.org/wiki/File:Stanis%C5%82aw_So%C5%82tan_szermierz.jpg
- `strazdas`: File:Poetas Antanas Strazdas.jpg, Edward Mateusz Jan Römer, 1877 (Public domain pd) https://commons.wikimedia.org/wiki/File:Poetas_Antanas_Strazdas.jpg
- `stulginskis`: File:Lithuania-1922-Stulginskis.jpg, Sijtze Reurich, 2015-01-01 (Public domain pd) https://commons.wikimedia.org/wiki/File:Lithuania-1922-Stulginskis.jpg
- `traugutt`: File:Romuald traugutt in russian uniform.jpg, Unknown, but this image is over 140 years old, so it's PD for sure., This photo was made before 1862. Traugut (Public domain pd) https://commons.wikimedia.org/wiki/File:Romuald_traugutt_in_russian_uniform.jpg
- `tyszkiewicz`: File:Tiskevicius Juozapas 1835-1891.JPG, Aleksander Władysław Strauss, between 1880 and 1885date QS:P,+1880-00- (Public domain pd) https://commons.wikimedia.org/wiki/File:Tiskevicius_Juozapas_1835-1891.JPG
- `vaizgantas`: File:TumasVaižgantasJ.jpg, Adomas Kliučinskis, uploaded by Rimantas Lazdynas, 2011-05-28 (Public domain pd) https://commons.wikimedia.org/wiki/File:TumasVai%C5%BEgantasJ.jpg
- `valancius`: File:Szyrma Valancius.jpg, Jan Szyrma, 1874-03-01 (Public domain pd) https://commons.wikimedia.org/wiki/File:Szyrma_Valancius.jpg
- `vileisis_j`: File:Vileisis.jpg, Jonas Vileišis (Public domain pd) https://commons.wikimedia.org/wiki/File:Vileisis.jpg
- `vileisis_p`: File:Petras Vileišis (1851-1926).jpg, cropped by me (Public domain pd) https://commons.wikimedia.org/wiki/File:Petras_Vilei%C5%A1is_(1851-1926).jpg
- `visinskis`: File:Povilas Višinskis 2.jpg, Freres Czyž (photo studio in Vilnius), circa 1903date QS:P,+1903-00-00T00:00:00 (CC0 cc0) https://commons.wikimedia.org/wiki/File:Povilas_Vi%C5%A1inskis_2.jpg
- `voldemaras`: File:Augustinas Voldemaras.jpg, George Grantham Bain Collection (Library of Congress), Unrecorded (Public domain pd) https://commons.wikimedia.org/wiki/File:Augustinas_Voldemaras.jpg
- `vydunas`: File:Vydunas.jpg, Vydūnas (Public domain pd) https://commons.wikimedia.org/wiki/File:Vydunas.jpg
- `ycas`: File:Martynas Ycas.jpg, Unknown authorUnknown author, between 1912 and 1914date QS:P,+1912-00- (Public domain pd) https://commons.wikimedia.org/wiki/File:Martynas_Ycas.jpg
- `zemaite`: File:Žemaitė su A. ir A. Bulotomis (cropped).jpg, Blowwhite, 2024-11-17 16:22:12 (CC0 cc0) https://commons.wikimedia.org/wiki/File:%C5%BDemait%C4%97_su_A._ir_A._Bulotomis_(cropped).jpg
- `zukauskas`: File:Silvestras-Žukauskas.jpg, Arz, 2008-02-21 (Public domain pd) https://commons.wikimedia.org/wiki/File:Silvestras-%C5%BDukauskas.jpg
