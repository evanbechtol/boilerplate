You have been given a task to design a proof-of-concept application, which will allow users to manage their inventories.



The application should implement the following minimum requirements:

            - Should allow users to add inventory items to the list of items

            - Should allow users to remove inventory items from the list of items

            - Should allow users to modify the name of the item

            - Should allow users to modify the available quantity of the item

            - Should be able to mark an item as tax-exempt using a checkbox



Inventory items will have the following structure:

{ name: string, quantity: number, taxExempt: boolean }



Additional requirements (but not for day 1):

- Should be able to toggle between showing or hiding items that are not in stock there are no items available

            - Should be able to show or hide tax exempt items

            - Sort the list of items by their names

            - Sort by the quantity available
