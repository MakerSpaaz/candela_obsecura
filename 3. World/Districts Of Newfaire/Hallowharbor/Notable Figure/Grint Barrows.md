---
pronouns: they/them
name: Grint Barrows
Description: a harbormaster with an iron fist who’s known for taking bribes, though their rate is high and ever-climbing.
Connections: 
tags:
  - POI
  - hallow_harbor
  - Glass_SeaDocks
  - NPC
district: Hallow Harbor
---
> [!infobox|wmtl]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Designer(6).jpeg|ws-med]] 

Name: `INPUT[text:name]`
\
Pronoun : `INPUT[inlineSelect(option(she/her), option(he/him), option(they/them), option(other)):pronouns]`
\
District: `INPUT[inlineSelect(option(Shriveline), 
option(Red Lamp), 
option(Briar Green), 
option(Hallow Harbor),
option(Nine Irons),
option(South Soffit),
option(The Shriveline),
option(The Eaves),
option(The Sidle),
option(Red Lamp),
option(The Steel),
option(Silverslip),
option(The Stream),
option(Groundswell),
option(The Varnish)):district]`
\
Description: `INPUT[text:Description]`
\
Connections: `INPUT[text:Connections]`

