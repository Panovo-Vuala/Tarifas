| TableID | Name       | QueryDEFINITION                                                                                                                                                         |
| ------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 10309   | Calendario | ADDCOLUMNS(<br>    CALENDAR(DATE(2024,1,1), DATE(2027,12,31)),<br>    "Año", YEAR([Date]),<br>    "Mes", FORMAT([Date], "MMMM"),<br>    "MesNúmero", MONTH([Date])<br>) |
