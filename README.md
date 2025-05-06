# Use-Delta-Tables-in-Apache-Spark
📘 Delta Lake Tables in Microsoft Fabric - README (Nederlands)
📝 Overzicht
Deze notebook bevat een oefening om te werken met Delta Lake-tabellen in een Microsoft Fabric Lakehouse. Hierbij hebben we gegevens geüpload, Delta-tabellen aangemaakt (zowel beheerde als externe), SQL-query's uitgevoerd en streaminggegevens verwerkt.

🧱 Stappen in deze oefening
1. Werkruimte en Lakehouse maken
Een nieuwe Microsoft Fabric-werkruimte gemaakt.

Een nieuw Lakehouse gecreëerd binnen de werkruimte.

2. Gegevens uploaden
Het CSV-bestand products.csv gedownload en geüpload naar een nieuwe map products in de Lakehouse.

3. Data verkennen in DataFrame
Spark DataFrame aangemaakt met een gespecificeerd schema om het CSV-bestand in te lezen.

4. Delta-tabellen maken
Een beheerde Delta-tabel (managed_products) aangemaakt.

Een externe Delta-tabel (external_products) aangemaakt met behulp van het ABFS-pad.

5. Verschillen verkennen tussen beheerde en externe tabellen
DESCRIBE FORMATTED SQL-commando gebruikt om opslaglocaties te vergelijken.

Beide tabellen verwijderd en geverifieerd dat alleen het externe tabelbestand bleef bestaan.

6. SQL gebruiken om Delta-tabel aan te maken
Tabel products aangemaakt vanuit de bestaande Delta-bestanden.

Gegevens geraadpleegd en bekeken met SQL-query’s.

7. Versiebeheer met Delta
Gegevens geüpdatet (10% korting op Mountain Bikes).

Historiek van wijzigingen bekeken met DESCRIBE HISTORY.

Data uit versie 0 vergeleken met de huidige versie.

8. Analyse met SQL
Tijdelijke view products_view gemaakt.

Aantal producten, minimum-, maximum- en gemiddelde prijzen per categorie weergegeven.

Topcategorieën weergegeven op basis van aantal producten.

9. Streaminggegevens verwerken
Een streamingbron gecreëerd met IoT-apparaatdata.

Delta-tabel IotDeviceData als sink gebruikt.

Nieuwe streamingdata toegevoegd en resultaten geraadpleegd.

✅ Conclusie
In deze oefening heb ik Delta Lake-functionaliteiten in Microsoft Fabric onderzocht, inclusief batch- en streamingdata, versiebeheer, SQL-analyse en het verschil tussen beheerde en externe tabellen.
