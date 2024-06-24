---
banner: "![[candela_obscura.jpg]]"
marksText1: Scar1
marksText2: Scar2
marksText3: Scar3
sldrSway: 0
sldrRead: 0
sldrHide: 0
sldrCunningMaxDrives: 0
sldrCunningDrives: 0
sldrResCunning: 0
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
name: Slash McBottom
pronouns: 
circle: 
style: 
catalyst: 
question: 
slider1: 3
prog1: 1
sldrMove: 0
sldrStrike: 0
sldrControl: 0
sldrResNerve: 0
sldrNerveMaxDrives: 0
sldrNerveDrives: 0
sldrMaxDrives: 3
sldrSurvey: 0
sldrFocus: 0
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
---







Name: `INPUT[text(showcase):name]` 
Pronoun(s): `INPUT[text(showcase):pronouns]`
Circle: `INPUT[text(showcase):circle]`


Style: `INPUT[text(showcase):style]`<abbr title="What is your character’s overall feel and aesthetic?"> :OcInfo24: </abbr>
Catalyst: `INPUT[text(showcase):catalyst]`<abbr title="Briefly describe why your character joined Candela Obscura—what happened
to make them devote their life to this cause?"> :OcInfo24: </abbr>
Question: `INPUT[text(showcase):question]`<abbr title="Explain what your character hopes to find out over the course of their
investigations—what knowledge are they pursuing that motivates them to charge into
danger? (This may align with your Catalyst or represent a completely different desire.)"> :OcInfo24: </abbr>

____________________________________________________________________________
> [!infobox|right wmtl]+
> # `VIEW[{name}][text]`
> ![[Designer(6).jpeg|ws-med]] 
> ###### NERVE 
> | Skill | Stat | 
> | ---- | ---- | 
> |Move |  `VIEW[{sldrMove}][text]` |
> | Strike | `VIEW[{sldrStrike}][text]` | 
> | Control |  `VIEW[{sldrControl}][text]` |
> | Resistance | `VIEW[{sldrResNerve}][text]` |
> 
> ##### CUNNING 
> | Skill | Stat | 
> | ---- | ---- | 
> | Sway | `VIEW[{sldrSway}][text]` | 
> | Read | `VIEW[{sldrRead}][text]` | 
> | Hide | `VIEW[{sldrHide}][text]`  | 
> | Resistance | `VIEW[{sldrResCunning}][text]` |
>
> ##### Stats 2 
> | Skill | Stat | 
> | ---- | ---- | 
> | Survey | `VIEW[{sldrSurvey}][text]` | 
> | Focus | `VIEW[{sldrFocus}][text]` | 
> | Sense | `VIEW[{sldrSense}][text]`  | 
> | Resistance | `VIEW[{sldrResIntuition}][text]` |
###### **NERVE:** 
> [!info|wfit] NERVE  
> ```text-progress-bar
> Drives:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> 
> ```text-progress-bar
>Max Dr:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> ```
>>
>> | MOVE   `VIEW[{sldrMove}][text]`    | STRIKE    `VIEW[{sldrStrike}][text]`    | CONTROL    `VIEW[{sldrControl}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | 
>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | 
>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMove]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrStrike]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrControl]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResNerve]`  |
 
###### **CUNNING:** 

> [!info|wfit] **CUNNING**
> ```text-progress-bar
> Drives:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> 
> ```text-progress-bar
>Max Dr:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> ```
>> 
>> | Sway    `VIEW[{sldrSway}][text]`  | Read    `VIEW[{sldrRead}][text]`    | Hide    `VIEW[{sldrHide}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | 
>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | 
>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSway]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrRead]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrHide]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResCunning]`  |


###### **INTUITION:** 
> [!info|wfit] **INTUITION**
> ```text-progress-bar
> Drives:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> 
> ```text-progress-bar
>Max Dr:0/3
> transition:⣦
> fill:📗
> empty:⣿
> prefix:⎸
> suffix:⎹
> length:3
> ```
>> | Survey    `VIEW[{sldrSurvey}][text]`  | Focus    `VIEW[{sldrFocus}][text]`    | Sense    `VIEW[{sldrSense}][text]`      | RESISTANCE `VIEW[{sldrResIntuition}][text]` |
>> | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
>> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSurvey]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrFocus]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSense]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResIntuition]`  | 
____________________________________________________________________________

###### **ROLE:**   Weird ([[Templates/Role Types/Abilities/Weird|Weird]])
🔹 `INPUT[text:role1]` 🔹 `INPUT[text:role2]`  🔹 `INPUT[text:role3]`  
____________________________________________________________________________

###### **SPECIALITY:** Occultist ([[Occultist]])
🔹 `INPUT[text:speciality1]`  🔹 `INPUT[text:speciality2]`  🔹 `INPUT[text:speciality3]`  
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








