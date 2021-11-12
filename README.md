# RSP-Vergelijk
Repo om verschillende respec varianten naast elkaar te proberen

volgende versies worden vergeleken

| Versie	                    | Pages	                                              | Gebaseerd op         |
|-----------------------------|-------------------------------------------------------|----------------------|
| Geonovum  Eigen versie      | https://geonovum.github.io/RSP-Vergelijk/GNM-Eigen    | IM Geluid            |
| Logius Eigen versie	     | https://geonovum.github.io/RSP-Vergelijk/Logius-Eigen | IM Geluid            |
| Logius Geonovum versie      | https://geonovum.github.io/RSP-Vergelijk/Logius-GNM   | IM Geluid            |
| W3C Eigen versie	          | https://geonovum.github.io/RSP-Vergelijk/W3C-Eigen    | IM Geluid            |
| W3C Geonovum versie         | https://geonovum.github.io/RSP-Vergelijk/W3C-GNM      | IM Geluid            |
| NLGOV (Logius) versie       | https://geonovum.github.io/RSP-Vergelijk/NLGOV-IM     | IM Geluid            |
| NLGOV (Logius) versie       | https://geonovum.github.io/RSP-Vergelijk/NLGOV-WP     | Whitepaper           |
| NLGOV (Logius) versie       | https://geonovum.github.io/RSP-Vergelijk/NLGOV-MD     | Markdown Testfile    |



Links naar js libraries

| Versie	                | Link in index.html	 | Leeftijd    |
|-------------------------|------------------------|-------------|
| Eigen Geonovum          | <script class="remove" src="https://tools.geostandaarden.nl/respec/builds/respec-geonovum.js" async></script>	        | 18 maanden oud |
| Eigen W3C 	           | <script class="remove" src="https://tools.geostandaarden.nl/respec/vergelijk/w3c/respec-w3c.js" async></script>	        | 27 dagen oud |
| W3C-Geonovum 	      | <script class="remove" src="https://tools.geostandaarden.nl/respec/vergelijk/w3c/respec-geonovum.js" async></script>	   | 27 dagen oud |
| Eigen Logius            | <script class="remove" src="https://tools.geostandaarden.nl/respec/vergelijk/logius/respec-logius.js" async></script>   | 6 maanden oud |
| Logius Geonovum         | <script class="remove" src="https://tools.geostandaarden.nl/respec/vergelijk/logius/respec-geonovum.js" async></script> |	6 maanden oud |
| NLGOV = Geonovum+Logius | <script class="remove" src="https://tools.geostandaarden.nl/respec/vergelijk/nlgov/respec-logius.js" async></script>    |	0 dagen oud |

NB: de Geonovum versie is opgegaan in de Logius versie, deze staat in de nlgov map.



*Bevindingen*

| Datum      | Publicatie | Bevinding                                 | Status        | Oplossing                                      | Issue#      |
|------------|------------|-------------------------------------------|---------------|------------------------------------------------|-------------| 
| 12-11-2021 | NLGOV-IM   | 548 warnings op dfn bij paragraaf teken   | Oplosbaar     | Vervang <a class="anchor" id door <a class="anchor" href=‘’ id in file data/IMG-cat-respec.html |             |
| 12-11-2021 | NLGOV-MD   | Foute weergave Markdown                   | Opgelost      | format="markdown" verwijderen uit in config.js |             |











