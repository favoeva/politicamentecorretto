---
layout: page
title: Opendata
permalink: /opendata/
---


In tabella troverete tutti i riferimenti ai contenuti e ai dati raccolti o prodotti da questo progetto con la loro licenza di riuso.
La sezione è in aggiornamento.

{: .table .table-striped #opendata}
Nome            |Dataset         |Licenza         |Link Licenza    |Fonte           |Formato         |Utilizzo        |Note
:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------
{% for member in site.data.opendata %} {{member.Nome}} | [Dataset]({{member.Dataset}}) | {{member.Licenza}} | [Link Licenza]({{member.Linklicenza}}) | [Fonte]({{member.Fonte}}) | {{member.Formato}} | {{member.Utilizzo}} | {{member.Note}}
{% endfor %}