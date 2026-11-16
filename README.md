# useful-blueprints

Samling af Home Assistant-blueprints.

## Blueprints

| Blueprint | Beskrivelse |
|-----------|-------------|
| [IKEA BILRESA (2 knapper) - lys med fade og natdæmpning](blueprints/automation/hsk-dk/ikea_bilresa_light_fade.yaml) | Styrer ét lys med IKEA BILRESA to-knaps via Zigbee2MQTT: fade op, svagt lys om natten, dobbelttryk for fuld lysstyrke og hold-inde for at dæmpe. |

## Installation

Klik på knappen, eller brug **Indstillinger → Automationer → Blueprints → Importér blueprint** og indsæt URL'en til filen.

[![Importér blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhsk-dk%2Fuseful-blueprints%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fhsk-dk%2Fikea_bilresa_light_fade.yaml)

## Struktur

Mapperne følger Home Assistants egen struktur (`blueprints/<domæne>/<forfatter>/<navn>.yaml`), så filer kan kopieres direkte ind i `config/blueprints/`.
