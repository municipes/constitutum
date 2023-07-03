# Constitūtum

![GitHub](https://img.shields.io/github/license/municipes/constitutum?style=for-the-badge)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/municipes/constitutum?sort=semver&style=for-the-badge)
![Packagist Dependency Version](https://img.shields.io/packagist/dependency-v/municipes/constitutum/drupal/core-recommended?style=for-the-badge)
![Packagist Downloads](https://img.shields.io/packagist/dt/municipes/constitutum?style=for-the-badge)

[Constitūtum] è un modulo Drupal che gestisce l'entità Appuntamento.
L'architettura dei campi è basata sulla [v2.0](https://docs.google.com/spreadsheets/d/1D4KbaA__xO9x_iBm08KvZASjrrFLYLKX/edit#gid=1529184526)
dell'architettura dell'informazione dei siti web dei comuni,
il content type che importa questo modulo è il [CT Appuntamento](https://docs.google.com/spreadsheets/d/1D4KbaA__xO9x_iBm08KvZASjrrFLYLKX/edit#gid=1472036419)

## Requisiti
- Drupal: >= 10
- Profilo Drupal: `minimal`
- Moduli contrib: `field_group`, `focal_point`, `imce`, `auto_entitylabel`, `media_library`, `inline_entity_form`, `ui_patterns_field_formatters`, `viewsreference`
- Moduli Municipes: `lexicum`, `fundamentum`, `domicilium`

## Installazione
Per aggiungere il modulo alla tua installazione esegui:
```bash
$ composer require municipes/constitutum
$ drush -y pm:install constitutum
```

## Implementazione tipo Appuntamento
| Architettura                               | Implementazione                                              | Note                                                                                                                                     |
|--------------------------------------------|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Nome e cognome                             | field_nome, <br/>field_cognome                               | L'informazione è stata divisa in due campi                                                                                               |
@TODO


## License

Copyright (C) 2023 https://github.com/municipes

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Questo è un software libero: puoi ridistribuirlo e/o modificarlo secondo i termini della GNU General Public License versione 3 pubblicata dalla Free Software Foundation.

Questo programma è distribuito nella speranza che possa essere utile, ma SENZA ALCUNA GARANZIA; senza nemmeno la garanzia implicita di COMMERCIABILITÀ o IDONEITÀ PER UNO SCOPO PARTICOLARE. Vedere la GNU General Public License per maggiori dettagli.
