---
name: test
circle: circleTest
role: roleTest
speciality: specTest
---
> [!checks]
> - **GROUP**
> 	- Next to checkboxes
> 	- [ ] %% %%
> 	- [ ] %% %%
> 	- [ ] %% %%
> 	- [ ] %% %%
> 	- [ ] %% %%
> - **New Row**
> 	- Description
> 	- [ ] %% %%
> 	- [ ] %% %%
> 	- [x] %% %%
> 	- [x] %% %%
> 	- [x] %% %%
> - 
> 	- Empty root bullet is necessary to group bullets together
> 	- [x] %% %%
> 	- [x] %% %%
> 	- [x] %% %%
> 	- [ ] %% %%
> 	- [ ] %% %%


> [!recite|color-blue]
> This is the text in a recite 

> [!recite|background-blue]

> [!recite|background-color-blue]


> [!infobox|left wikipedia]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Candela_Obscura_wordmark.png|center]] 
> ![[Cordelia_Glask.jpg|ws-med]] 
> # <font color="#82f008">Details</font>
> - <font color="#82f008">ROLE</font>
> 	- <font color="#82f008">Role:</font> <font color="#82f008">`= this.role`</font>
> 	- <font color="#82f008">Ability:</font> <font color="#82f008">`= this.roleAbility`</font>
> 
> - <font color="#82f008">SPECIALITY</font>
> 	- <font color="#82f008">Speciality:</font> <font color="#82f008">`= this.speciality`</font>
> 	- <font color="#82f008">Ability:</font> <font color="#82f008">`= this.specAbility`</font>





> [!infobox|right wikipedia]+
> # <font color="#66ff00">`= this.name`</font>
> ![[Candela_Obscura_wordmark.png|center]] 
> ![[Cordelia_Glask.jpg|ws-med]] 
> # <font color="#82f008">**DETAILS**</font>
> 
>  <font color="#82f008">**Circle**</font>
> - <font color="#66ff00">Circle: <font color="#66ff00">`= this.circle`</font>
> - <font color="#82f008">ROLE / SPECIALITY</font>
> 	- <font color="#82f008">ROLE: `= this.role`</font>
> 	- <font color="#66ff00">Speciality:<font color="#66ff00">`= this.speciality`</font>


> [!column|list] Columns for regular lists only
> - List Item
> 	- Sub list item
> - List Item
> - List Item
> 	- Sub list item
> 	- Sub list item
> - List Item
> - List Item
> - List Item
> - List Item
> 	- Sub list item
> 	- Sub list item
> 	- Sub list item
> - List Item
> - List Item
> - List Item