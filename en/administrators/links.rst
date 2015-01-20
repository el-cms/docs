Links
#####

Links are attributed to menus.

Creating a link
===============
When you create a link, you have these options:

* **Link tab ** Main params
  * *Menu:* The menu in which the link will be created.
  * *Parent:* If the link is another link's child, select its parent here.
  * *Title:* The link title.
* **Access tab:** Manage authorizations
  * *Role:* Here you can select the roles allowed to see the link.
* **Misc tab:** Other params
  * *Class:* CSS classes applied to the link.
  * *Desription:* Title attribute
  * *Rel:* Rel attribute
  * *Target:* Target attribute
  * *Params: A list of parameters for the link.*

## Params
The _Params_ field allows you to define additionnal parameters for the link. As this field is linked to the [ParamsBehaviour](../developpers/behaviours/params), parameters should be defined as a list of one key/value per line.
For now the only parameter recognized is the `linkAttr`, which should contain a list of link attributes, as follow:

    [options:linkAttr attr1=val1 attr2=val2]
