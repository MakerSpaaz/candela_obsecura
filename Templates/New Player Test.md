---
banner: "![[candela_obscura.jpg]]"
marksText1: Scar1
marksText2: Scar2
marksText3: Scar3
sldrSway: 1
sldrRead: 1
sldrHide: 0
sldrCunningMaxDrives: 8
sldrCunningDrives: 5
sldrResCunning: 3
specText1: Spec1
specText2: Spec2
specText3: Spec3
specText4: Spec4
specText5: Spec5
specText6: Spec6
relship1: Relshp 1
relship2: Relshp 2
relship3: Relshp 3
famRelship1: Relshp 1
famRelship2: Relshp 2
famRelship3: Relshp 3
gearText1: Spec1
gearText2: Spec2
gearText3: Spec3
gearText4: Spec4
gearText5: Spec5
gearText6: Spec6
illumText1: Illum 1
illumText2: Illum 2
illumText3: Illum 3
name: 
pronouns: 
circle: 
style: 
catalyst: 
question: 
slider1: 3
prog1: 1
sldrMove: 1
sldrStrike: 0
sldrControl: 1
sldrResNerve: 3
sldrNerveMaxDrives: 7
sldrNerveDrives: 7
sldrMaxDrives: 3
sldrSurvey: 1
sldrFocus: 0
sldrSense: 2
sldrResIntuition: 1
sldrIntuitionMaxDrives: 9
sldrIntuitionDrives: 2
role1: 
role2: 
role3: 
scar1: 
scar2: 
scar3: 
speciality1: 
speciality2: 
speciality3: 
speciality4: 
sldrMarkBleed: 0
sldrMarkBrain: 0
sldrMarkBody: 0
---



--- start-multi-column: ID_4xdz
```column-settings
Number of Columns: 3
Largest Column: standard
```

![[candela_logo.png|250]]

--- column-break ---

Name: `INPUT[text(showcase):name]`
Pronoun(s): `INPUT[text(showcase):pronouns]`
Circle: `INPUT[text(showcase):circle]`


--- column-break ---

Style: `INPUT[text(showcase):style]`
Catalyst: `INPUT[text(showcase):catalyst]`
Question: `INPUT[text(showcase):question]`


--- end-multi-column
____________________________________________________________________________

###### **NERVE:** 
*Max Drives:*      `VIEW[{sldrNerveMaxDrives}][text]`
*Drives:*      `VIEW[{sldrNerveDrives}][text]`
> [!info] NERVE  
> | MOVE    `VIEW[{sldrMove}][text]`  | STRIKE    `VIEW[{sldrStrike}][text]`    | CONTROL    `VIEW[{sldrControl}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | Max Drives `VIEW[{sldrNerveMaxDrives}][text]` | Drives `VIEW[{sldrNerveDrives}][text]`  |
> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMove]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrStrike]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrControl]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResNerve]`  | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrNerveMaxDrives]` | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrNerveDrives]` |
 
###### **CUNNING:** 
*Max Drives:*      `VIEW[{sldrCunningMaxDrives}][text]`
*Drives:*      `VIEW[{sldrCunningDrives}][text]`
> [!info] CUNNING    Max Drives: `VIEW[{sldrNerveMaxDrives}][text]` Drives: `VIEW[{sldrNerveDrives}][text]`
> | Sway    `VIEW[{sldrSway}][text]`  | Read    `VIEW[{sldrRead}][text]`    | Hide    `VIEW[{sldrHide}][text]`      | RESISTANCE `VIEW[{sldrResNerve}][text]` | Max Drives `VIEW[{sldrCunningMaxDrives}][text]` | Drives `VIEW[{sldrCunningDrives}][text]`  |
> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSway]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrRead]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrHide]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResCunning]`  | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrCunningMaxDrives]` | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrCunningDrives]` |

###### **INTUITION:** 
*Max Drives:*      `VIEW[{sldrIntuitionMaxDrives}][text]`
*Drives:*      `VIEW[{sldrIntuitionDrives}][text]`

> [!info] INTUITION    Max Drives: `VIEW[{sldrIntuitionMaxDrives}][text]` Drives: `VIEW[{sldrIntuitionDrives}][text]`
> | Survey    `VIEW[{sldrSurvey}][text]`  | Focus    `VIEW[{sldrFocus}][text]`    | Sense    `VIEW[{sldrSense}][text]`      | RESISTANCE `VIEW[{sldrResIntuition}][text]` | Max Drives `VIEW[{sldrIntuitionMaxDrives}][text]` | Drives `VIEW[{sldrIntuitionDrives}][text]`  |
> | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
> | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSurvey]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrFocus]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrSense]`   |`INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrResIntuition]`  | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrIntuitionMaxDrives]` | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(9), stepSize(1)):sldrIntuitionDrives]` |

____________________________________________________________________________

###### **ROLE:** 
:CoInstance: `INPUT[textArea:role1]`  :CoInstance: `INPUT[textArea:role2]`  :CoInstance: `INPUT[textArea:role3]`  
____________________________________________________________________________

###### **SPECIALITY:** 
:CoInstance: `INPUT[text:speciality1]`  :CoInstance: `INPUT[text:speciality2]`  :CoInstance: `INPUT[text:speciality3]`  :CoInstance: `INPUT[text:speciality4]` 
____________________________________________________________________________
###### **MARKS:**
| BODY    `VIEW[{sldrMarkBody}][text]`  | BRAIN    `VIEW[{sldrMarkBrain}][text]`    | BLEED    `VIEW[{sldrMarkBleed}][text]`      | 
| -------------------------- | -------------------------- | -------------------------- | 
| `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBody]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBrain]`   | `INPUT[slider(showcase, addLabels, minValue(0), maxValue(3), stepSize(1)):sldrMarkBleed]`   |
____________________________________________________________________________

###### **SCARS:** 
:CoInstance: `INPUT[text:scar1]`  :CoInstance: `INPUT[text:scar2]`  :CoInstance: `INPUT[text:scar3]`  
____________________________________________________________________________

###### **GEAR:** *During each assignment, choose up to three*
:CoInstance: `INPUT[text:gear1]`  :CoInstance: `INPUT[text:gear2]`  :CoInstance: `INPUT[text:gear3]`  :CoInstance: `INPUT[text:gear4]`  :CoInstance: `INPUT[text:gear5]`  
____________________________________________________________________________
###### **RELATIONSHIPS:** 
:CoInstance: `INPUT[text:relship1]`  :CoInstance: `INPUT[text:famRelship1]`
:CoInstance: `INPUT[text:relship2]`  :CoInstance: `INPUT[text:famRelship2]` 
:CoInstance: `INPUT[text:relship3]`  :CoInstance: `INPUT[text:famRelship3]`
____________________________________________________________________________
###### **ILLUMINATION KEYS:** 
:CoInstance: `INPUT[text:illumKey1]`  :CoInstance: `INPUT[text:allumKey2]`  :CoInstance: `INPUT[text:allumKey3]`  
____________________________________________________________________________
###### **NOTES:** 
`INPUT[textArea:notes]`
____________________________________________________________________________










