# useful-blueprints

Samling af Home Assistant-blueprints.

## Blueprints

| Blueprint | Beskrivelse | Importér |
|-----------|-------------|----------|
| [IKEA BILRESA (2 knapper) - lys med fade og natdæmpning](blueprints/automation/hsk-dk/ikea_bilresa_light_fade.yaml) | Styrer ét lys med IKEA BILRESA to-knaps via Zigbee2MQTT: fade op, svagt lys om natten, dobbelttryk for fuld lysstyrke og hold-inde for at dæmpe. | [![Importér](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fikea_bilresa_light_fade.yaml) |
| [Børneværelse - læselampe (v3)](blueprints/automation/hsk-dk/child_reading_light.yaml) | Aqara WXKG11LM via Zigbee2MQTT: enkelt tryk tænder dag- eller natscene, hold tænder natscene, dobbelttryk slukker. Timer slukker lyset efter en periode. | [![Importér](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fchild_reading_light.yaml) |
| [Vindue åbent for længe v3](blueprints/automation/hsk-dk/window_open_too_long.yaml) | Sender påmindelser, når et vindue har været åbent for længe. Ventetiden afhænger af udetemperatur og aktiv varme. Notifikationen ryddes, når vinduet lukkes. Valgfrit: sænker temperaturen på varmen, mens vinduet er åbent, og gendanner den ved lukning. | [![Importér](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fwindow_open_too_long.yaml) |
| [Device Maintenance Alert](blueprints/automation/hsk-dk/device_maintenance_alert.yaml) | Opretter vedligeholdelsesalarmer med notifikationer og valgfrie todo-opgaver, når en enhed kræver service (filter, salt, rengøring). | [![Importér](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fdevice_maintenance_alert.yaml) |
| [Wavin / Klima - mulig fast åben ventil](blueprints/automation/hsk-dk/wavin_stuck.yaml) | Overvåger climate-enheder og udløser en samlet reaktion, hvis et rum stadig varmer, selv om temperaturen er over setpunktet. | [![Importér](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fwavin_stuck.yaml) |

## Installation

Klik på knappen ved den blueprint du vil bruge, eller brug **Indstillinger → Automationer → Blueprints → Importér blueprint** og indsæt URL'en til filen.

## Struktur

Mapperne følger Home Assistants egen struktur (`blueprints/<domæne>/<forfatter>/<navn>.yaml`), så filer kan kopieres direkte ind i `config/blueprints/`.
