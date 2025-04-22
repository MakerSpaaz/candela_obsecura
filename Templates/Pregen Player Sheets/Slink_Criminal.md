---
banner: "![[candela_obscura.jpg]]"
marksText1: Scar1
marksText2: Scar2
marksText3: Scar3
sldrSway: 1
sldrRead: 1
sldrHide: 2
sldrCunningMaxDrives: 0
sldrCunningDrives: 0
sldrResCunning: 1
specText1: Spec1
specText2: Spec2
specText3: Spec3
specText4: Spec4
specText5: Spec5
specText6: Spec6
relship1: Person
relship2: Person
relship3: Person
relship4: Person
famRelship1: Relationship
famRelship2: Relationship
famRelship3: Relationship
famRelship4: Relationship
gearText1: Spec1
gearText2: Spec2
gearText3: Spec3
gearText4: Spec4
gearText5: Spec5
gearText6: Spec6
illumText1: Illum 1
illumText2: Illum 2
illumText3: Illum 3
name: Slink Criminal
pronouns: 
circle: 
style: 
catalyst: 
question: 
slider1: 3
prog1: 1
sldrMove: 1
sldrStrike: 1
sldrControl: 1
sldrResNerve: 1
sldrNerveMaxDrives: 0
sldrNerveDrives: 0
sldrMaxDrives: 3
sldrSurvey: 1
sldrFocus: 1
sldrSense: 0
sldrResIntuition: 0
sldrIntuitionMaxDrives: 0
sldrIntuitionDrives: 0
role0: 
role1: 
role2: 
role3: 
scar1: 
scar2: 
scar3: 
speciality0: 
speciality1: 
speciality2: 
speciality3: 
speciality4: 
sldrMarkBleed: 0
sldrMarkBrain: 0
sldrMarkBody: 0
select: 2
StyleInfo: 
role: Slink
speciality: Criminal
roleAbility: "Slink: Scout"
specAbility: "Criminal: Street Smarts"
---

> [!even-columns]
> > [!Personal] Personal
> >
> > Name: `INPUT[text(showcase):name]` 
> >
> > Pronoun(s): `INPUT[text(showcase):pronouns]`
> > 
> > Circle: `INPUT[text(showcase):circle]`
>
> > [!Detaills] Details
> >
> > Style: `INPUT[text(showcase):style]`<abbr title= "What is your character’s overall feel and aesthetic?" > :RiInformation2Line: </abbr>
> > 
> > Catalyst: `INPUT[text(showcase):catalyst]`<abbr title="Briefly describe why your character joined Candela Obscura—what happened
to make them devote their life to this cause?"> :RiInformation2Line: </abbr>
> > 
> > Question: `INPUT[text(showcase):question]`<abbr title="Explain what your character hopes to find out over the course of their
investigations—what knowledge are they pursuing that motivates them to charge into
danger? (This may align with your Catalyst or represent a completely different desire.)"> :RiInformation2Line: </abbr>

____________________________________________________________________________
> [!infobox|right wikipedia]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Candela_Obscura_wordmark.png|center]] 
> ![[Designer(6).jpeg|wmed]] 
> # <font color="#82f008">Nerve</font>
> - <font color="#82f008">Move: </font>  <font color="#82f008">`VIEW[{sldrMove}][text]`</font>
> - <font color="#82f008">Strike:</font> <font color="#82f008">`VIEW[{sldrStrike}][text]`</font>
> - <font color="#82f008">Control:</font>  <font color="#82f008">`VIEW[{sldrControl}][text]`</font>
> - <font color="#82f008">Resistance:</font> <font color="#82f008">`VIEW[{sldrResNerve}][text]`</font>
> 
> # <font color="#82f008">CUNNING </font>
> - <font color="#82f008">Sway:</font> <font color="#82f008">`VIEW[{sldrSway}][text]`</font>
> - <font color="#82f008">Read:</font> <font color="#82f008">`VIEW[{sldrRead}][text]`</font> 
> - <font color="#82f008">Hide:</font> <font color="#82f008">`VIEW[{sldrHide}][text]`</font>  
> - <font color="#82f008">Resistance:</font> <font color="#82f008">`VIEW[{sldrResCunning}][text]`</font>
>  
> # <font color="#82f008">INTUITION </font>
> - <font color="#82f008">Survey:</font> <font color="#82f008">`VIEW[{sldrSurvey}][text]`</font> 
> - <font color="#82f008">Focus:</font> <font color="#82f008">`VIEW[{sldrFocus}][text]`</font> 
> - <font color="#82f008">Sense:</font> <font color="#82f008">`VIEW[{sldrSense}][text]`</font>  
> - <font color="#82f008">Resistance:</font> <font color="#82f008">`VIEW[{sldrResIntuition}][text]`</font>

###### **NERVE:** 
>[!info|wfit] 
>> [!checks]
>> - *<font color="#82f008">DRIVES</font>*
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> - *<font color="#82f008">MAX DRIVES</font>*
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %% 
>> -
>>>
>>> | MOVE   `VIEW[{sldrMove}][text]`    | STRIKE    `VIEW[{sldrStrike}][text]`    | CONTROL    `VIEW[{sldrControl}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | 
>>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | 
>>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMove]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrStrike]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrControl]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResNerve]`  |
 
###### **CUNNING:** 
> [!info|wfit] 
>> [!checks]
>> - *<font color="#82f008">DRIVES</font>*
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> - *<font color="#82f008">MAX DRIVES</font>*
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> -
>>>
>>> | Sway    `VIEW[{sldrSway}][text]`  | Read    `VIEW[{sldrRead}][text]`    | Hide    `VIEW[{sldrHide}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | 
>>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | 
>>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSway]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrRead]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrHide]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResCunning]`  |


###### **INTUITION:** 
> [!info|wfit] 
>> [!checks]
>> - *<font color="#82f008">DRIVES</font>*
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> - *<font color="#82f008">MAX DRIVES</font>*
>> 	- [x] %% %%
>> 	- [x] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> 	- [ ] %% %%
>> - 
>>>
>>> | Survey    `VIEW[{sldrSurvey}][text]`  | Focus    `VIEW[{sldrFocus}][text]`    | Sense    `VIEW[{sldrSense}][text]`      | RESISTANCE `VIEW[{sldrResIntuition}][text]` |
>>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
>>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSurvey]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrFocus]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSense]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResIntuition]`  | 
____________________________________________________________________________
###### **ROLE:**   
<font color="#66ff00">Role:</font> `INPUT[inlineSelect(option(Face), option(Muscle), option(Scholar), option(Slink),option( Weird), showcase):role]`    <font color="#66ff00">Role Ability:</font> `INPUT[inlineSelect(option(Face: I Know a Guy), option(Face: Sweet Talk), option(Face: Cool Under Pressure), option(Muscle: Behind Me),option(Muscle: Adrenaline Rush),option(Muscle: Endurance),option(Scholar: Well-Read),option(Scholar: Occult Researcher),option(Scholar: Meticulous Notes),option(Slink: Scout),option(Slink: Saw This Coming),option(Slink: Death Defy),option(Weird: Great Wards),option(Weird: Let Them In),option(Weird: Ritual)):roleAbility]`
____________________________________________________________________________
###### **SPECIALITY:** 
<font color="#66ff00">Speciality:</font> `INPUT[inlineSelect(option(Journalist), option(Magician), option(Explorer), option(Soldier),option(Doctor),option(Professor),option(Criminal),option(Detective),option(Medium),option(Occultist)):speciality]`    <font color="#66ff00">Speciality Ability:</font> `INPUT[inlineSelect(
option(Journalist: Insider Access:), option(Journalist: Open Book), option(Journalist: Lie Detector), option(Journalist: Press Conference), option(Journalist: In The Trenches), option(Journalist: Well-Researched), option(Magician: Misdirection), option(Magician: Escape Artist), option(Magician: Practiced Patter), option(Magician: Uncanny Eye), option(Magician: Flourish), option(Magician: The Prestige), option(Explorer: Obscure Lexicon), option(Explorer: Field Experience), option(Explorer: Mind Over Matter), option(Explorer: Tenacious), option(Explorer: Narrow Escape), option(Explorer: Not Again), option(Soldier: Basic Training), option(Soldier: Geared Up), option(Soldier: Sharpshooter),
option(Soldier: Compartmentalization), option(Soldier: Volunteer Duty), option(Soldier: Tactician), option(Doctor: Patch Up), option(Doctor: Non-Combatant), option(Doctor: Dissection), option(Doctor: Resuscitation), option(Doctor: Lifesaver), option(Doctor: Anatomical Strike), option(Professor: Steel Mind), option(Professor: University Resources), option(Professor: Learn From My Mistake), option(Professor: Verbose), option(Professor: Chemical Concoction), option(Professor: Better Part of Valor), option(Criminal: Street Smarts), option(Criminal: Leverage), option(Criminal: Hardened), option(Criminal: Born in The Shadows), option(Criminal: Tricks of The Trade), option(Criminal: Sticky Fingers), option(Detective: Mind Palace), option(Detective: Interrogation), option(Detective: Back Against The Wall), option(Detective: Inspection), option(Detective: Stakeout), option(Detective: One Step Ahead), option(Medium: Miasma), option(Medium: Bending Spoons), option(Medium: Cold Read), option(Medium: Premonitions), option(Medium: Last Moments), option(Medium: Commune), option(Occultist: Ghostblade), option(Occultist: Blood of The Covenant), option(Occultist: Speak Their Language), option(Occultist: Play The Bait), option(Occultist: Extend Your Senses), option(Occultist: Forbidden Ritual)):specAbility]`
____________________________________________________________________________
###### **MARKS:**
| BODY    `VIEW[{sldrMarkBody}][text]`  | BRAIN    `VIEW[{sldrMarkBrain}][text]`    | BLEED    `VIEW[{sldrMarkBleed}][text]`      | 
| -------------------------- | -------------------------- | -------------------------- | 
| `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBody]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBrain]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBleed]`   |
____________________________________________________________________________
###### **SCARS:** 
🩹 `INPUT[text:scar1]`  🩹 `INPUT[text:scar2]`  🩹 `INPUT[text:scar3]`  
____________________________________________________________________________
###### **GEAR:** *During each assignment, choose up to three*
⚙ `INPUT[text:gear1]`  ⚙ `INPUT[text:gear2]`  ⚙ `INPUT[text:gear3]`  ⚙ `INPUT[text:gear4]`  ⚙ `INPUT[text:gear5]`  
____________________________________________________________________________
###### **RELATIONSHIPS:** 
🧍 `INPUT[text:relship1]`  👩‍👦‍👦 `INPUT[text:famRelship1]`
🧍 `INPUT[text:relship2]`  👩‍👦‍👦 `INPUT[text:famRelship2]` 
🧍 `INPUT[text:relship3]`  👩‍👦‍👦 `INPUT[text:famRelship3]`
🧍 `INPUT[text:relship4]`  👩‍👦‍👦 `INPUT[text:famRelship4]`
____________________________________________________________________________
###### **ILLUMINATION KEYS:** 
🗝 `INPUT[text:illumKey1]`  🗝 `INPUT[text:allumKey2]`  🗝 `INPUT[text:allumKey3]`  
____________________________________________________________________________
###### **NOTES:** 
`INPUT[textArea:notes]`
____________________________________________________________________________
