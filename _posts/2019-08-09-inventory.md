---
layout: post
title:  "Inventory"
date:   2019-08-09 09:30:30 +0200
categories: jekyll update
---

## Inventory management

We are now working on a new feature, Inventory Management.

If you **do not** want to use the new inventory, you can still create a new item every time "the old way".

This will be the new Inventory page:
![inventory page](/assets/inventory.png "Inventory Page")


We have added a field for the [SKU](https://en.wikipedia.org/wiki/Stock_keeping_unit) (Stock Keeping Unit) identifier and more.

![inventory Edit](/assets/inventory_edit.png "Inventory Edit")

If the `Disabled` checkbox is checked, the item will **not be found** in the _'Add Materials'_ section in a Repair.


Inventory items can be **created or added** to a repair from the searchable dropdown.
![add material](/assets/add_material.png "add material")


* When an item is added to a repair, it's `stock` **goes down** by one.
* When the item is removed from a repair, the `stock` **goes back up** by one.
* The `Price` field can be **overridden**. Example:
   * If you select _"Brake Pads $2.45"_ the `Price` field will have 2.45 - but you can change it in case you need to add a discount.


Every item has it's own page where the history is visible.

![inventory history](/assets/inventory_history.png "Inventory history")

It shows in which repairs an item was used, and which employee added it, and when.

It also shows you how many items you have sold, the total and the average selling price.
