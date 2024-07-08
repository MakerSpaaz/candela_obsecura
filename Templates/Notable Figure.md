---
pronouns: other
name: Notable Figure
Description: ""
Connections: 
tags:
  - POI
---

> [!infobox|right wmtl]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Designer(6).jpeg|ws-med]] 

<font color="#92d050">Name:</font> `INPUT[text:name]`
\
<font color="#92d050">Pronoun :</font> `INPUT[inlineSelect(option(she/her), option(he/him), option(they/them), option(they/she), option(they/he),option(other)):pronouns]`
\
<font color="#92d050">District:</font> `INPUT[inlineSelect(option(Shriveline), option(Red Lamp), option(Briar Green), option(Hallow Harbor),option(Nine Irons),option(South Soffit),option(The Shriveline),option(The Eaves),option(The Sidle),option(Red Lamp),option(The Steel),option(Silverslip),option(The Stream),option(Groundswell),option(The Varnish)):district]`

> <font color="#92d050">Description:</font> `INPUT[textArea(showcase):Description]`    

<font color="#92d050">Connections:</font> `INPUT[text(showcase):connections]`
