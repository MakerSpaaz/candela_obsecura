---
pronouns: she/her
name: Adina Renfield
Description: The owner of The Counter Offer, originally from the Haven Hills, and an expert in counterfeit paperwork. There is no identification, ticket, or signature she cannot recreate.
Connections: 
tags:
  - groundswell
  - market
  - Pawn_Shop
  - NPC
---
> [!infobox|wmtl]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Designer(6).jpeg|ws-med]] 

Name: `INPUT[text:name]`
\
Pronoun : `INPUT[inlineSelect(option(she/her), option(he/him), option(they/them), option(other)):pronouns]`
\
District: `INPUT[inlineSelect(option(Shriveline), option(Red Lamp), option(Briar Green), option(Varnish)):district]`
\
Description: `INPUT[text:Description]`
\
Connections: `INPUT[text:Connections]`