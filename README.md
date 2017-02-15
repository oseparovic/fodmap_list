# Adding food items

Supported food items use the following format:

    {
        "name": "Agave",
        "fodmap": "high",
        "category": "Sweeteners"
    }
    
* **name** - plaintext name of the food item
* **fodmap** - fodmap classification of the item. Currently only "low" and "high" are supported
* **category** - food category this item belongs to

Notes:

* If you are new to JSON, please note that all food items *except the last item* must have a **comma** after the closing `}`


# Sources: 

* http://www.ibsdiets.org/wp-content/uploads/2016/03/IBSDiets-FODMAP-chart.pdf
* http://www.katescarlata.com/lowfodmapdietchecklists/
