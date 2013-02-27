# Digital Closet Organizer #
This service is a digital closet for people to record, organize, manage, analyze and share their clothing and accessories. Items are added by users, assigned a unique identifier, and are then globally accessible by all other users. The items will be classified per a standard system but can also be classified by the user once it's in their specific closet. In order to add an item into the collection, the user must identify, at a minimum, the article and type of clothing, designer, and color. The user will also be able to create their own subcategories but not the primary classification. The classifications will not be hierarchical and items can be classified into different subcategories. In addition, users can identify items that are part of a set through linking. Users will want to search the collection based on any number of factors that include the classification types, most generally starting with a particular item type. Ideally, a user can use the service to build outfits and share.

## ID Attribute Values ##
* Add Item: Add article of clothing, accessory or shoe to your collection. Applied to a FORM to create a new entry.
* Add New to The Inventory: Add a new article of clothing, accessory or shoe to the global inventory collection for sharing.
* Search My Closet: Query used to locate an item in your closet. Applied to a FORM to search.
* Search The Inventory: Query the global inventory collection to locate an item that does not yet exist in your personal closet. Applied to a FORM for search.
* Update Item: Use a FORM to update an existing item in your closet.
* Add a Subcategory to My Closet: Use a FORM to add a subcategory from your closet. You cannot add classifications.
* Remove a Subcategory from your Closet: Use a FORM to remove.

## Class Attribute Values ##
* SearchCloset - Search for an item in your personal closet; applied to a FORM tag.
* SearchInventory - Search the global inventory collection; applied to a FORM tag.
* classification - Classification of an item (shoes, clothing or accessories).
* designer - Name of the Designer.
* color - Color of the item.
* title - Title of the item.
* size - Size of the item.
* keyword - Words from the description.
* subcategory - The subcategory of the item.
* allitems - The list of all items in the global inventory collection.
* myitems - The of all items in your closet.
* itemimg - Image of the item; applied to a DIV tag.
* imgdesc - Description of image
* itemtext - Details of an item

## Name Attribute Values ##
* item[ID] - Unique identifier for each item 
* item[type] - Use SELECT[option] to identify the type: Accessory, Clothing, Shoes
* item[title] - Brief title for the item; applied to an INPUT[text] element.
* item[classification] - Classification of an item; applied to a SELECT[option] element.
* item[subcategory] - Use SELECT[option] to identify the subcategory.
* item[designer] - The designer of the item; applied to an INPUT[text] element.
* item[color] - The color of the item; applied to an INPUT[text] element.
* item[description] - Description of the item; applied to a TEXTAREA element.
* item[embellishment] - Any embellishment on the item (glitter, rhinestone, fringe, etc.); applied to an INPUT[text] element.
* item[size] - Size of the item; applied to an INPUT[text] element.
* item[notes] - User notes of the item; applied to a TEXTAREA element.
* item[date] - Year the item was purchased; applied to an INPUT[text] element.
* item[price] - Price of the item; applied to an INPUT[text] element.
* item[place] - Place item was purchased; applied to an INPUT[text] element.

## Rel Attribute Values ##
* Item - Link to a particular item; applied to an 'a href' tag.
* Designer - Link to a designer's home page; applied to an 'a href' tag.
* Closet - Link to the personal closet home page; applied to an 'a href' tag.
* Home - Link to the Digital Closet home page; applied to an 'a href' tag.
<<<<<<< HEAD
* Sample - Link to a sample "My Closet" page; applied to an 'a rel' tag.
=======
* Sample - Link to a sample "My Closet" page; applied to an 'a rel' tag.
>>>>>>> Added new files
