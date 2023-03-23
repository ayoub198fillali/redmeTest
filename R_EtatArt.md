![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.001.png)

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.002.png)











![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.003.png)** 






![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.004.jpeg)






























<a name="_hlk95816584"></a>**- Advanced Charging - System for Electric Vehicles**
![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.005.png)

Réalisé par :

FILLALI AYOUB

Encadré par :

Mme. Senda ROMDHANI

**2023**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.006.png)
![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.007.png)![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.008.png)

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.009.png)




RAPPORT

ÉTAT DE L’ART
![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.010.png)








![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.011.png)

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.012.png)**Introduction générale**

Les batteries à charge bidirectionnelles sont des dispositifs qui permettent à l'énergie électrique de circuler dans les deux sens, de la source d'alimentation vers la charge et vice versa. Ces batteries peuvent être utilisées dans une variété d'applications, telles que le stockage de l'énergie solaire pour une utilisation ultérieure, l'alimentation de véhicules électriques et la régulation de la demande d'énergie dans les réseaux électriques. Cependant, l'optimisation de la performance de ces batteries peut être complexe en raison de la variabilité des profils de charge et de décharge.

Dans ce rapport d'état de l'art, on se concentre sur l'analyse des Smart Data Models existants pour les batteries bidirectionnelles. L'objectif est d'étudier les différentes approches de modélisation existantes et d'évaluer leur pertinence pour notre contexte. En particulier, on s'intéressera aux aspects d'interopérabilité des modèles et à leur capacité à intégrer des données provenant de sources multiples.

En analysant les modèles existants, on pourra identifier les avantages et les limites de chaque approche, ainsi que les opportunités pour le développement d'un modèle propre à nous. Ce modèle interopérable devra permettre de prédire la performance de la batterie en fonction de différents facteurs, tels que la température, la charge et le taux de décharge. En utilisant des techniques de machine learning et des algorithmes d'apprentissage automatique, on pourra améliorer la précision des prévisions et optimiser les stratégies de gestion de l'énergie. Cette étude est importante car elle pourrait avoir des implications significatives pour l'optimisation de la performance des batteries à charge bidirectionnelles et contribuer à la transition vers une énergie plus propre et plus efficace.

1. **Motivation :**

La transition vers une économie à faibles émissions de carbone a stimulé l'intérêt pour les technologies de stockage de l'énergie électrique, en particulier pour les batteries bidirectionnelles. Ces batteries peuvent jouer un rôle clé dans l'intégration des sources d'énergie renouvelable et dans la stabilisation des réseaux électriques, en permettant un stockage de l'énergie électrique pour une utilisation ultérieure ou une injection directe dans le réseau. Cependant, l'optimisation de la performance de ces batteries reste un défi important en raison de la complexité des profils de charge et de décharge, ainsi que de la variabilité des conditions environnementales.

**3**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.013.png)Le développement d'un smart data model pour les batteries à charge bidirectionnelles peut contribuer à résoudre ces défis et à améliorer l'efficacité énergétique. Un tel modèle peut permettre une meilleure prédiction de la performance de la batterie et de son comportement dans différentes conditions, ainsi qu'une optimisation de sa gestion de l'énergie. En utilisant des techniques de machine learning et des algorithmes d'apprentissage automatique, on peut améliorer la précision des prévisions et augmenter l'efficacité de la batterie. De plus, en assurant l'interopérabilité des modèles, on peut faciliter l'intégration de différents systèmes et sources de données, et permettre une meilleure prise de décision pour les gestionnaires de réseaux électriques et les propriétaires de batteries.

Dans ce contexte, l'objectif de ce rapport est d'analyser les Smart Data Models existants pour les batteries bidirectionnelles, d'évaluer leur pertinence et leur adéquation pour notre contexte, et de proposer un modèle propre à nous qui soit interopérable et efficace. Cette étude est importante car elle pourrait avoir des implications significatives pour l'optimisation de la performance des batteries à charge bidirectionnelles et pour la transition vers une énergie plus propre et plus durable.

1. ` `**Contexte et historique :**

Au cours des dernières décennies, l'augmentation de la demande en énergie électrique et les préoccupations environnementales ont conduit à l'émergence de technologies de stockage de l'énergie électrique, telles que les batteries. Les batteries à charge bidirectionnelles ont été développées pour répondre à des besoins spécifiques, notamment le stockage de l'énergie solaire pour une utilisation ultérieure, l'alimentation de véhicules électriques et la régulation de la demande d'énergie dans les réseaux électriques.

Les batteries à charge bidirectionnelles sont capables de fournir et de stocker de l'énergie électrique, et peuvent être utilisées pour réguler la demande d'énergie électrique dans les réseaux, ce qui est important pour la stabilité et la fiabilité des réseaux électriques. De plus, l'intégration de sources d'énergie renouvelable dans les réseaux électriques peut être difficile en raison de leur variabilité. Les batteries à charge bidirectionnelles peuvent aider à résoudre ce problème en stockant l'énergie excédentaire produite par les sources d'énergie renouvelable pour une utilisation ultérieure.

Cependant, l'optimisation de la performance de ces batteries reste un défi important en raison de la variabilité des profils de charge et de décharge, ainsi que de la variabilité des conditions environnementales. Pour résoudre ces défis, la modélisation de données intelligentes (smart data modeling) peut jouer un rôle crucial en permettant une meilleure prédiction de la performance de la batterie et de son comportement dans différentes conditions, ainsi qu'une optimisation de sa gestion de l'énergie.

**4**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.014.png)C'est dans ce contexte que nous nous intéressons à l'analyse des Smart Data Models existants pour les batteries à charge bidirectionnelles et à la proposition d'un modèle propre à nous interopérable et efficace. Ce modèle devra permettre d'optimiser la performance de la batterie en fonction de différents facteurs, tels que la température, la charge et le taux de décharge. En somme, cette étude est importante car elle pourrait avoir des implications significatives pour l'optimisation de la performance des batteries à charge bidirectionnelles et contribuer à la transition vers une énergie plus propre et plus efficace.

1. **Objectifs :**

•	Analyser les Smart Data Models existants pour les batteries bidirectionnelles.

•	Évaluer la pertinence et l'adéquation des modèles existants pour notre contexte.

•	Identifier les avantages et les limites de chaque approche de modélisation.

•	Proposer un modèle propre à nous qui soit interopérable et efficace.

•	Améliorer la précision des prévisions de performance de la batterie en utilisant des techniques de machine learning et des algorithmes d'apprentissage automatique.

•	Optimiser les stratégies de gestion de l'énergie en utilisant le modèle proposé pour améliorer l'efficacité énergétique des batteries bidirectionnelles.

•	Contribuer à la transition vers une énergie plus propre et plus durable en améliorant l'efficacité énergétique des batteries bidirectionnelles.

1. **Questions de recherche**
- Est-ce qu’il existe des modèles de données pour la gestion de batterie bidirectionnelle/par induction ?

- Quelles sont les données que les modèles de gestion de batteries représentent ?

- Quelles sont les limitations des modèles de données de gestion de batteries existants ?

- Est-ce que ces modèles sont interopérables avec d'autres systèmes et plates-formes ? Sinon, comment peut-on les rendre interopérables pour faciliter l'adoption et l'extension de ces solutions ?

- Est-ce qu’ils représentent le cas d’usage de recharge par induction/bidirectionnelle ? 

- Comment peut-on contribuer à surmonter ces limitations ?


1. **Méthodologie**

**5**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.015.png)Pour réaliser cet état de l'art, nous avons effectué une recherche systématique dans les bases de données académiques telles que IEEEXplore, ScienceDirect et SpringerLink en utilisant les mots-clés tels que "batteries bidirectionnelles", "modélisation de batteries", "gestion de l'énergie" et "battery smart data models". Nous avons limité la recherche aux articles publiés dans les dix dernières années et en langue anglaise et français.

Nous avons également examiné les références bibliographiques des articles pertinents pour identifier d'autres sources potentielles. Les articles sélectionnés ont été analysés en utilisant une approche de lecture critique pour extraire les informations pertinentes concernant les modèles de batteries existants, leur pertinence pour notre contexte, les avantages et les limites de chaque approche de modélisation, les techniques de machine learning pour améliorer la précision des prévisions de performance de la batterie, et les stratégies de gestion de l'énergie optimales.

Cependant, cette étude présente quelques limites, notamment la limitation aux sources en langue anglaise/francais publiées, ainsi que la limitation de notre recherche aux bases de données académiques. De plus, certaines sources peuvent être inaccessibles en raison de restrictions d'accès ou de coût. Ces limitations peuvent affecter l'exhaustivité de notre recherche et donc les résultats de notre étude.

1. **Tableau comparatif des Data Models existants pour les batteries à charge bidirectionnelles :**

Lors de mes recherches sur les modèles de données pour les batteries, j'ai constaté qu'il y a un manque évident de ressources disponibles dans la littérature. Bien que les batteries à charge bidirectionnelles soient de plus en plus utilisées dans une variété de domaines, y compris les systèmes d'énergie solaire et les voitures électriques, il semble que peu de recherche ait été menée sur la modélisation de données spécifiques à ces batteries. En conséquence, il peut être difficile pour les ingénieurs et les chercheurs de développer des modèles précis et fiables pour les batteries bidirectionnelles, ce qui peut entraver le développement de nouveaux systèmes et technologies.

Il est possible que le manque de ressources sur les modèles de données pour les batteries à charge bidirectionnelles ou les batteries en générale soit dû en partie au fait que cette technologie est relativement nouvelle. Cependant, il est également possible que la recherche dans ce domaine ait été menée dans des cadres non liés à la modélisation de données, ou qu'elle n'ait pas encore été publiée. 

Cependant, en tant que chercheurs, notre rôle est de dépasser ces défis et de travailler à développer des modèles de données précis pour les batteries à charge bidirectionnelles afin d'aider à surmonter les obstacles actuels et à ouvrir la voie à de nouvelles applications et technologies. En continuant à explorer les modèles de données existants et à en développer de nouveaux, nous pourrions contribuer à améliorer l'efficacité et la durée de vie des batteries bidirectionnelles, ainsi qu'à favoriser leur intégration dans une variété de systèmes énergétiques et de transport. Par conséquent, il est important de poursuivre les recherches dans ce domaine pour répondre aux besoins actuels et futurs de l'industrie et de la société dans son ensemble.

**6**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.016.png)

Voici un tableau présentant les modèles de données existants pour la gestion des batteries, avec leurs avantages et leurs limites.

**7**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.017.png)

|**Modèle de données**|**Description**|**Avantages**|**Limites**|**Domain**|**Interopérable**|
| :-: | :-: | :-: | :-: | :-: | :-: |
|<p>FIWARE smart-data-models Battery</p><p></p>|<p></p><p>Modèle de données développé par Fiware pour la gestion des batteries. Il comprend des informations sur l'état de charge, la tension, le courant, la température, la capacité, l'autonomie restante, etc.</p><p></p>|<p>- Compatible avec les plateformes Fiware existantes</p><p>- Facile à intégrer avec d'autres applications Fiware</p>|<p>- Limité aux fonctionnalités de base de la gestion de la batterie</p><p>- Peut nécessiter des personnalisations pour s'adapter aux besoins spécifiques</p>|[Battery](https://github.com/smart-data-models/dataModel.Battery)|OUI|
|OCPP Battery|<p></p><p>Modèle de données qui étend le standard OCPP pour inclure des informations spécifiques à la batterie</p><p></p>|Permet une communication plus détaillée et plus précise entre la borne de recharge et le véhicule électrique|Conçu spécifiquement pour les bornes de recharge de véhicules électriques|[Battery](https://github.com/OpenChargingCloud/ocpp/)|Non|
|Indian Urban Data Exchange (IUDX)|<p></p><p>Les modèles de données de la batterie IUDX incluent des informations sur l'état de charge, la capacité, la tension et le courant, ainsi que des informations sur les modes de fonctionnement, tels que la charge, la décharge et l'auto-décharge. </p>|<p>Modèle simple et facile à utiliser</p><p>Convient pour des cas d'utilisation basiques tels que la surveillance de l'état de charge et de la température de la batterie.</p>|Modèle très limité en termes d'attributs et de fonctionnalités par rapport à d'autres modèles de données pour la batterie.|<p>[SolarEnergy](https://voc.iudx.org.in/SolarEnergy)</p><p>[EnergyMeter](https://voc.iudx.org.in/EnergyMeter)</p><p>[Battery](https://docs.iudx.org.in/schema/energy/battery.html)</p>|Non|
|European Telecommunication Standards Institute (ETSI)|<p></p><p>Modèle de données intelligent pour les batteries, conçu pour être utilisé dans les systèmes de stockage d'énergie intelligents</p>|- Permet de surveiller et de contrôler les batteries en temps réel - Améliore l'efficacité énergétique et la durée de vie de la batterie|- Conçu pour les systèmes de stockage d'énergie intelligents, pas adapté aux autres types d'applications|[Battery](https://www.etsi.org/deliver/etsi_gs/mec/001_099/008/01.01.01_60/gs_mec008v010101p.pdf)|Non|
|<p>PHOENIX (893079)</p><p>UMU, OdinS, ARDEN, UBITECH, SAGOE and LTU</p>|<p></p><p>Le modèle de données PHOENIX pour la batterie est un modèle complet et détaillé qui fournit une grande variété d'informations sur l'état de la batterie, notamment la capacité, la température, la tension, le courant, la résistance interne et les cycles de charge.</p><p></p>|Modèle de données complet et détaillé qui fournit de nombreuses informations sur l'état de la batterie.|<p>Le modèle est assez complexe et peut nécessiter une certaine expertise pour être pleinement exploité.</p><p>Il peut ne pas convenir pour des cas d'utilisation plus simples ou moins avancés.</p>|[Battery](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjWlID5ztj9AhW6VaQEHeoQBAcQFnoECAYQAQ&url=https%3A%2F%2Feu-phoenix.eu%2Fwp-content%2Fuploads%2F2022%2F03%2FD3.1.pdf&usg=AOvVaw1M62ESkNCNdgOLhE67ZFJj)|Non|
|B2B Battery|Modèle de données pour les applications de stockage d'énergie dans les bâtiments|<p>Basé sur Brick Schema, conçu pour les systèmes de stockage d'énergie dans les bâtiments</p><p></p>|Pas adapté à d'autres types d'applications|[Battery_Bat](https://brickschema.org/schema/1.1/Brick/Battery)|Non|
|OpenFMB Battery|<p></p><p>Est conçu pour les applications de stockage d'énergie. Il est basé sur le standard Open Field Message Bus (OpenFMB) et est disponible sur le site Web de l'Institute of Electrical and Electronics Engineers (IEEE)</p><p></p>|Standard ouvert, conçu pour les systèmes de stockage d'énergie|Basé sur OpenFMB, pas adapté à d'autres types d'applications|[Battery*](https://standards.ieee.org/ieee/1536/2277/)|Non|
|Battery Management System (BMS)|Modèle de données pour la gestion des batteries dans les véhicules électriques|Conçu pour les systèmes de gestion de batteries dans les véhicules électriques|Basé sur OCPP, pas adapté à d'autres types d'applications|[Battery*](https://www.openchargealliance.org/)|Non|
|<p>**8**</p><p>![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.018.png)Sujets de recherche (doctorants)</p>|<p></p><p>Le Modèle de données adopté par les doctorants c’est Fiware</p><p></p>|-Pareil à Fiware -|-Pareil à Fiware -|[SmartCity*](https://www.sciencedirect.com/science/article/abs/pii/S0378377416304061)|Oui|


Voici une liste de ces modèles de batterie et de leurs attributs associés :

- FIWARE Battery( Entity: StorageBatteryDevice )

- "address"
- "alternateName"
- "application" 
- "areaServed"
- "averageLife"
- "batteryType"
- "brandName"
- "capacityCnnn"
- "chargeDischargeReactivity"
- "chargeEfficiency"
- "chargePower"
- "chargingModeAllowed"
- "communication"
- "dataProvider"
- "dateCreated"
- "dateLastReported"
- "dateModified"
- "description"
- "dimension"
- "dischargeEfficiency"
- "dischargePower"
- "documentation"
- "durationPeakPower"
- "id"
- "installationCondition"
- "installationMode"
- "lifeCycleNumber"
- "location"
- "manufacturerName"
- "massEnergyDensity"
- "maxOutputPower"
- "maximumVoltageEOC"
- "minimumVoltageEOD"
- "modelName"
- "name"
- "nominalAmpere"
- "nominalCapacity"
- "nominalFrequency"
- "nominalVoltage"
- "operatingAltitude"
- "operatingAmpere"
- "operatingFrequency"
- "operatingTemperature"
- "operatingVoltage"
- "overloadAccepted"
- "overloadAcceptedTime"
- "owner"
- "peakPower"
- "possibilityOfUse"
- "protectionIK"
- "protectionIP"
- "rechargeEnergySource"
- "refDevice"
- "refPointOfInterest"
- "roundTripEfficiency"
- "seeAlso"
- "selfDischargeRate"
- "serialNumber"
- "source"
- "storableEnergy"
- "toolBMS"
- "type"
- "typeEnergySource"
- "typeOfUse"
- "usableEnergy"
- "volEnergyDensity"
- "weight"


- OCPP Battery

- `	`"BatteryCapacity"
- `	`"BatteryVoltage"

**9**
- ![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.019.png)	"BatteryCurrent"
- `	`"BatteryTemperature"
- `	`"StateOfCharge"
- `	`"ChargingMode"
- `	`"BatteryType"
- `	`"VendorName"


- Indian Urban Data Exchange (IUDX)

- `	`"battery\_soc"
- `	`"battery\_voltage"
- `	`"battery\_temperature"
- `  `"battery\_current"


- European Telecommunication Standards Institute (ETSI)

- "battery\_status"
- "battery\_capacity"
- "battery\_charge\_level"
- "battery\_voltage"
- "battery\_temperature"
- "battery\_current"
- "battery\_energy"
- "battery\_time\_remaining"
- "battery\_cycle\_count"
- "battery\_manufacturer"
- "battery\_model"
- "battery\_serial\_number"
- "battery\_firmware\_version"


- `	`PHOENIX : 

- `	`"battery\_id"
- `	`"state\_of\_charge"
- `	`"capacity"
- `	`"voltage"
- `	`"current"
- `	`"temperature"
- `	`"internal\_resistance"
- `	`"cycle\_count"
- `	`"charging\_time" 
- `	`"discharging\_time"



- B2B Battery :

- "battery\_status"
- "battery\_capacity"
- "battery\_charge\_level"
- "battery\_current"
- "battery\_voltage"
- "battery\_temperature"
- "battery\_power"



- OpenFMB	

- `	`"batteryID
- `	`"stateOfCharge"
- `	`"maxCapacity"

**10**
- ![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.020.png)	"currentCapacity"
- `	`"current"
- `	`"voltage"
- `	`"temperature"
- `	`"status"	


- Battery Management System (BMS)

- ` `"batteryID"
- ` `"stateOfCharge"
- ` `"maxCapacity"
- ` `"currentCapacity"
- ` `"current"
- ` `"voltage"
- ` `"temperature"
- ` `"status"


Le choix d'un modèle de données approprié est crucial pour garantir une intégration fluide et une gestion efficace des données. Dans ce contexte, nous avons examiné plusieurs modèles de données pour la gestion de batteries, notamment Fiware Smart-Data-Models Battery, OCPP Battery, Indian Urban Data Exchange (IUDX), European Telecommunication Standards Institute (ETSI), PHOENIX, B2B Battery, OpenFMB Battery, Battery Management System (BMS), et les sujets de recherche.

Chacun ayant ses avantages et limites. Parmi ces modèles, le FIWARE smart-data-models Battery semble être une option solide en raison de sa compatibilité avec les plateformes existantes Fiware et de sa facilité d'intégration avec d'autres applications Fiware. Il fournit également des informations de base sur l'état de charge, la tension, le courant, la température, la capacité, l'autonomie restante, etc.

De plus, il est important de souligner que certains modèles de données ne sont pas interopérables, ce qui signifie qu'ils peuvent ne pas être compatibles avec d'autres systèmes ou plates-formes.

Nous tenons à souligner que notre projet a pour objectif d'analyser les batteries en profondeur et de tirer parti des compétences de nos experts pour identifier les attributs pertinents à ajouter avec les contextes appropriés. En d'autres termes, nous visons à aller au-delà des limites actuelles de Fiware en matière de gestion de batteries en proposant des fonctionnalités plus avancées et en optimisant l'efficacité énergétique. Nous sommes convaincus que notre approche innovante nous permettra de proposer des solutions personnalisées et performantes pour répondre aux besoins spécifiques après.

En conclusion, le modèle FIWARE smart-data-models Battery est une option solide pour les projets de gestion de batteries en général, tandis qu’on doit essayer d'adapter le modèle aux besoins spécifiques de chaque projet. Cela peut inclure la recherche et le brainstorming pour définir de nouveaux attributs qui peuvent contribuer à la description de la batterie et rendre le modèle plus interopérable, ainsi que l'ajout d'attributs de la charge bidirectionnelle (V2B et V2G). Il est également important de définir les contextes pertinents pour chaque attribut afin de garantir une interopérabilité maximale avec les services IoT. En somme, l'utilisation du modèle FIWARE smart-data-models Battery peut être un bon point de départ, mais il est important de le personnaliser pour répondre aux besoins spécifiques de chaque projet.

**11**

![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.021.png)

1. **Notre contribution : nouveaux attributs pour batterie interopérable et efficace dans l'IoT.**





























**12**
![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.022.png)










FIN
![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.023.png)


























![](Aspose.Words.79924e66-321c-480e-a6ea-01085164af6e.024.png)
