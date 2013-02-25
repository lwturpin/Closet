# Digital Closet Organizer #
This service is a digital closet for people to record, organize, manage, analyze and share their clothing and accessories. Items are added by users, assigned a unique identifier, and are then globally accessible by all other users. The items will be classified per a standard system but can also be classified by the user once it's in their specific closet. In order to add an item into the collection, the user must identify, at a minimum, the article and type of clothing, designer, and color. The application will classify into broad categories and subcategories, such as type of article, color, designer. The user will also be able to create their own classification subcategories but not the primary classification. The classifications will not be hierarchical and items can be classified into different subcategories. In addition, users can identify items that are part of a set through linking. Users will want to search the collection based on any number of factors that include the classification types, most generally starting with a particular item type. Ideally, a user can use the service to build outfits and share.

## ID Attribute Values ##
* Add Item: Add article of clothing, accessory or shoe to your collection. Applied to a FORM to create a new entry.
* Add New to The Inventory: Add a new article of clothing, accessory or shoe to the global inventory collection for sharing.
* Search My Closet: Query used to locate an item in your closet. Applied to a FORM to search.
* Search The Inventory: Query the global inventory collection to locate an item that does not yet exist in your personal closet. Applied to a FORM for search.
* Update Item: Use a FORM to update an existing item in your closet.
* Update The Inventory: Use a FORM to update an item in the global inventory collection. Requires permission.
* Add a Subcategory to My Closet: Use a FORM to add a subcategory from your closet. You cannot add categories.
* Remove a Subcategory from My Closet: Use a FORM to delete a subcategory from your closet. You cannot delete categories from the global inventory collection.

## Class Attribute Values ##
* SearchCloset - Search for an item in your personal closet; applied to a FORM tag.
* SearchInventory - Search the global inventory collection; applied to a FORM tag.
* designer - Name of the Designer; applied to a SPAN tag.
* color - Color of the item; applied to a SPAN tag.
* accessorytitle - Title of the accessory; applied to a SPAN tag.
* shoetitle - Title of the shoes; applied to a SPAN tag.
* clothingtitle - Title of the clothing; applied to a SPAN tag.
* accessorysize - Size of the accessory; applied to a SPAN tag.
* shoesize - Size of the shoes; applied to a SPAN tag.
* clothingsize - Size of the article of clothing; applied to a SPAN tag.
* keyword - Words from the description; applied to a SPAN tag.
* subcategory - The subcategory of the item; applied to a SPAN tag.
* allitems - The list of all items in the global inventory collection; applied to a SPAN tag.
* myitems - The list of all items in your personal closet; applied to a SPAN tag.

## Name Attribute Values ##
* item[type] - Use SELECT[option] to identify the type: Accessory, Clothing, Shoes
* item[title] - Brief title for the item (40 characters or less); applied to an INPUT[text] element.
* item[subcategory] - Use SELECT[option] to identify the subcategory. This is separated by system and user-generated.
* item[designer] - The designer of the item; applied to an INPUT[text] element.
* item[color] - The color of the item; applied to an INPUT[text] element.
* item[description] - Description of the item; applied to a TEXTAREA element.
* item[embellishment] - Any embellishment on the item (glitter, rhinestone, fringe, etc.); applied to an INPUT[text] element.
* item[size] - Size of the item; applied to an INPUT[text] element.
* item[notes] - User notes of the item; applied to a TEXTAREA element.
* item[date] - Year the item was purchased; applied to an INPUT[text] element.
* item[price] - Price of the item; applied to an INPUT[text] element.
* item[place] - Place item was purchased; applied to an INPUT[text] element.
* item[related] - Related items; applied to SELECT[option] element listing all other items in the personal closet.

## Rel Attribute Values ##
* Item - Link to a particular item; applied to an 'a href' tag.
* Designer - Link to a designer's home page; applied to an 'a href' tag.
* Closet - Link to the personal closet home page; applied to an 'a href' tag.
* Home - Link to the Digital Closet home page; applied to an 'a href' tag.
* Stylesheet - LINK tag to the CSS stylesheet
