# DTM_Desktop-Mapping
## Eine Reise durch das Semester

Willkommen zu meiner kleinen Reise durch das Modul **DTM – Desktop-Mapping**. Zwischen Daten, Farben, Symbolen und gelegentlichem QGIS-Chaos entstanden im Laufe des Semesters ganz unterschiedliche Karten. Diese Seite zeigt die einzelnen Etappen, Ergebnisse und Erkenntnisse – mit viel Freude am Kartengestalten und natürlich **powered by dem „Helden der Karten“**.


<img width="10%" height="10%" alt="" src="https://github.com/LukasBHT/DTM_Desktop-Mapping/blob/main/ChatGPT%20Image%2023.%20Apr.%202026,%2016_33_29.png?raw=true" />

## EP 01 | Dasymetrische Choropletenkarten

### Vor- und Nachteile der dasymetrischen Darstellung

Die dasymetrische Karte stellt die Bevölkerung nur innerhalb der tatsächlich besiedelten Flächen dar. Unbewohnte Bereiche wie Wälder, Gewässer, Parks oder große Gewerbeflächen werden weitgehend ausgeschlossen. Dadurch entsteht ein räumlich differenzierteres und realitätsnäheres Bild der Bevölkerungsverteilung als bei einer klassischen Choroplethenkarte, die einen Wert gleichmäßig auf die gesamte Verwaltungseinheit überträgt. Besonders in unterschiedlich dicht bebauten Gebieten lassen sich Bevölkerungsschwerpunkte so besser erkennen.

Die Methode benötigt jedoch zusätzliche und möglichst aktuelle Daten zur Flächennutzung oder Bebauung. Ungenauigkeiten in diesen Daten wirken sich direkt auf das Ergebnis aus. Außerdem bleibt die Bevölkerung innerhalb der ausgewählten Siedlungsflächen meist rechnerisch gleichmäßig verteilt, obwohl die tatsächliche Einwohnerzahl beispielsweise zwischen Einfamilienhausgebieten und Großwohnsiedlungen stark variiert. Die Erstellung ist daher aufwendiger und das Ergebnis trotz der höheren räumlichen Genauigkeit weiterhin eine modellhafte Annäherung.

<img width="2382" height="1684" alt="" src="https://github.com/user-attachments/assets/a31066fc-72e5-4002-9d96-cd6e05e6e6f6" />

### Umsetzung der Methode

Zunächst wurden die Einwohnerzahlen den Berliner LOR-Planungsräumen zugeordnet und sowohl als absolute Werte als auch als Bevölkerungsdichte dargestellt. Für die dasymetrische Karte wurden die LOR anschließend mit den tatsächlichen Siedlungsflächen verschnitten. Die Einwohnerzahl jedes Planungsraums wurde auf dessen bewohnte Fläche bezogen und als Einwohner je Quadratkilometer Siedlungsfläche neu berechnet. Eine abgestufte Farbskala macht die so ermittelten Dichteunterschiede sichtbar.

### EP.02 | Gitterchoroplethenkarten
<img width="2382" height="1684" alt="" src="https://github.com/LukasBHT/DTM_Desktop-Mapping/blob/main/BlossomBerlin.png?raw=true" />
<img width="3308" height="2338" alt="image" src="https://github.com/user-attachments/assets/22e087e9-e498-43b2-9231-9dd364508df8" />

### EP.03 | Punktrasterkarten
<img width="3308" height="2338" alt="image" src="https://github.com/user-attachments/assets/b480aa72-086f-4f91-9142-d1ec7111ff3b" />


### EP.04 | Value-By-Alpha Mapping
<img width="3308" height="2338" alt="image" src="https://github.com/user-attachments/assets/27a450a5-f072-45f7-b2ab-4870f75a27e6" />


### EP.05 | Ursprung-Ziel-Karten
<img width="2338" height="1652" alt="image" src="https://github.com/user-attachments/assets/3ce957d3-63f8-471b-85c5-a5e8659f2023" />


### EP.06 | Tilemaps
<img width="2338" height="3308" alt="image" src="https://github.com/user-attachments/assets/7ad106fb-3506-43c5-8d52-e43e8aa4ea92" />


### EP.07 | Animation in QGIS
<img width="1009" height="781" alt="image" src="https://github.com/user-attachments/assets/e2761d43-6363-4033-8881-8031e0e35d92" />

<img width="1600" height="1291" alt="image" src="https://github.com/user-attachments/assets/d885e6c7-47ab-495d-9920-8604182d1cc0" />



### EP.08 | Mesh-Daten

### EP.09 | 3D-Gebäudemodelle
<img width="2338" height="1652" alt="image" src="https://github.com/user-attachments/assets/e8dd617b-1329-4b19-8bca-a041ad95e705" />

<img width="2560" height="1303" alt="image" src="https://github.com/user-attachments/assets/04f6500c-a82d-49a8-9fae-0ee9c9898363" />

