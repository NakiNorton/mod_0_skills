#Class: Menu

**Attributes**
* menuItems (object) (with key being the name of dish and value being price)
* restaurantName (string)
* dietaryComments (boolean)
* material (string)

**Methods**
* updatePrice (modifies the value of **menuItem** property(ies), either increasing or decreasing price)
* dietaryAlertMessage (is an alert needed? True or false. Uses the **dietaryComments** attribute to inform customer of ingredients which could cause allergic reaction)
* changeMenu (modifies the **menuItems** attribute i.e. adding a new item, or swapping one out)
* laminateMenu (laminate paper menu. Changes the **material** attribute of menu)
