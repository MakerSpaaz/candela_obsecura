---
name: Dr Howard Margrove
pronouns: he/him
district: 
Description: |-
  Dr. Margrove is very much an introvert, spending long hours in his book and oddity-filled office at the College, which is kept constantly pristine. His colleagues there viewed him as keeping too much to himself.

  Robbie Daymond described the character as "a real creep, a punchy lab wizard scientist. ... [He's] a man of mystery. He’s a compulsive, fastidious, hyper-intellectual reductionist, who doesn’t understand the madness that is unfolding around him and wants desperately to, and throughout this journey he will either learn to lean in or be consumed. Dr. Howard is not to be trifled with."
Connections: 
Abilities: 
Circle: 
circle: Vassal & The Veil
role: Scholar
speciality: Professor
notable_item1: Lab Equipment
notable_item2: 
specAbility: "Professor: Chemical Concoction"
---

> [!infobox|right wmtl]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Candela_Obscura_wordmark.png|center]] 
> ![[Howard_Margrove.jpg|ws-med]] 
> # <font color="#82f008">Details</font>
> - <font color="#82f008">ROLE</font>
> 	- <font color="#82f008">Role:</font> <font color="#82f008">`= this.role`</font>
> 	- <font color="#82f008">Ability:</font> <font color="#82f008">`= this.roleAbility`</font>
> 
> - <font color="#82f008">SPECIALITY</font>
> 	- <font color="#82f008">Speciality:</font> <font color="#82f008">`= this.speciality`</font>
> 	- <font color="#82f008">Ability:</font> <font color="#82f008">`= this.specAbility`</font>

<font color="#66ff00">Name:</font> `INPUT[text:name]`   <font color="#66ff00">Pronoun :</font> `INPUT[inlineSelect(option(she/her), option(he/him), option(they/them), option(they/she), option(they/he),option(other)):pronouns]`

<font color="#66ff00">Chapter House:</font> `INPUT[text(showcase):chapter_house]`    <font color="#66ff00">Circle Name:</font> `INPUT[inlineSelect(option(Needle & Thread), option(Tide & Bone), option(Vassal & The Veil), option(Crimson Mirror),option( Silver Screen), showcase):circle]`

<font color="#66ff00">District:</font> `INPUT[inlineSelect(option(The Shriveline), option(Red Lamp), option(Briar Green), option(Hallow Harbor),option(Nine Irons),option(South Soffit),option(The Shriveline),option(The Eaves),option(The Sidle),option(Red Lamp),option(The Steel),option(Silverslip),option(The Stream),option(Groundswell),option(The Varnish)):district]`

> <font color="#66ff00">Description:</font> `INPUT[textArea(showcase):Description]`    

<font color="#66ff00">Role:</font> `INPUT[inlineSelect(option(Face), option(Muscle), option(Scholar), option(Slink),option( Weird), showcase):role]`    <font color="#66ff00">Role Ability:</font> `INPUT[inlineSelect(option(Face: I Know a Guy), option(Face: Sweet Talk), option(Face: Cool Under Pressure), option(Muscle: Behind Me),option(Muscle: Adrenaline Rush),option(Muscle: Endurance),option(Scholar: Well-Read),option(Scholar: Occult Researcher),option(Scholar: Meticulous Notes),option(Slink: Scout),option(Slink: Saw This Coming),option(Slink: Death Defy),option(Weird: Great Wards),option(Weird: Let Them In),option(Weird: Ritual)):roleAbility]`
\
<font color="#66ff00">Speciality:</font> `INPUT[inlineSelect(option(Journalist), option(Magician), option(Explorer), option(Soldier), option(Doctor), option(Professor) ,option(Criminal), option(Detective), option(Medium),option(Occultist)):speciality]`    <font color="#66ff00">Speciality Ability:</font> `INPUT[inlineSelect(option(Journalist: Insider Access:), option(Journalist: Open Book), option(Journalist: Lie Detector), option(Journalist: Press Conference), option(Journalist: In The Trenches), option(Journalist: Well-Researched), option(Magician: Misdirection),option(Magician: Escape Artist),option(Magician: Practiced Patter),option(Magician: Uncanny Eye),option(Magician: Flourish),option(Magician: The Prestige),option(Explorer: Obscure Lexicon),option(Explorer: Field Experience),option(Explorer: Mind Over Matter),option(Explorer: Tenacious),option(Explorer: Narrow Escape),option(Explorer: Not Again),option(Soldier: Basic Training),option(Soldier: Geared Up),option(Soldier: Sharpshooter),option(Soldier: Compartmentalization),option(Soldier: Volunteer Duty),option(Soldier: Tactician),option(Doctor: Patch Up),option(Doctor: Non-Combatant),option(Doctor: Dissection),option(Doctor: Resuscitation),option(Doctor: Lifesaver),option(Doctor: Anatomical Strike),option(Professor: Steel Mind),option(Professor: University Resources),option(Professor: Learn From My Mistake),option(Professor: Verbose),option(Professor: Chemical Concoction),option(Professor: Better Part of Valor),option(Criminal: Street Smarts),option(Criminal: Leverage),option(Criminal: Hardened),option(Criminal: Born in The Shadows),option(Criminal: Tricks of The Trade),option(Criminal: Sticky Fingers),option(Detective: Mind Palace),option(Detective: Interrogation),option(Detective: Back Against The Wall),option(Detective: Inspection),option(Detective: Stakeout),option(Detective: One Step Ahead),option(Medium: Miasma),option(Medium: Bending Spoons),option(Medium: Cold Read),option(Medium: Premonitions),option(Medium: Last Moments),option(Medium: Commune),option(Occultist: Ghostblade),option(Occultist: Blood of The Covenant),option(Occultist: Speak Their Language),option(Occultist: Play The Bait),option(Occultist: Extend Your Senses),option(Occultist: Forbidden Ritual)):specAbility]`

<font color="#82f008">Notable Items: </font> `INPUT[text:notable_item1]`   `INPUT[text:notable_item2]`

<font color="#66ff00">Connections:</font> `INPUT[text(showcase):connections]`