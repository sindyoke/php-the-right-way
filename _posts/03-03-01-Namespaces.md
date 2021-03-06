﻿---
isChild: true
---

## Namespaces {#namespaces_title}

Kao što je gore navedeno, PHP zajednica se sastoji od mnogo developera koji stvaraju gomilu koda. To znači da kod jedne biblioteke verovatno koristi isto ime klase kao neka druga biblioteka. kada se obe biblioteke koriste u istom ?namespace, dolazi do kolizije i problema.

_Namespaces_ rešavaju ovaj problem. Kako je i opisano u PHP reference manual, namespaces se mogu uporediti sa direktorijumima operativnog sistema that _namespace_ files; dva istoimena fajla mogu postojati istovremeno u različitim direktorijumima. isto tako, dve PHP klase istog imena mogu postojati u različitim PHP namespaces. Vrlo jednostavno.

Važno je da namespace vaš kod da bi i drugi developeri mogli da ga koriste bez straha od kolizije sa drugim bibliotekama.

Jedan način na koji se preporučuje korišćenje namespaces je ?opisan (outlined) u [PSR-0][psr0], čiji je cilj da pruži standarizovanu konvenciju za fajlove, klase i namespace da bi omogučio postojanje plug-and-play koda.

* [Pročitajte o Namespaces][namespaces]
* [Pročitajte o PSR-0][psr0]

[namespaces]: http://php.net/manual/en/language.namespaces.php
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
