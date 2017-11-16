# Adding food items

Supported food items use the following format:

    {
        "id": "14",
        "name": "Almond butter",
        "fodmap": "low",
        "category": "Cooking ingredients, Herbs and Spices",
        "qty":"1 tbsp",
        "details": {"oligos":0,"fructose":0,"polyols":0,"lactose":0}
    },

* **id** - plaintext number representing the items ID. Must be unique to the entire database
* **name** - plaintext name of the food item, include serving max in brackets
* **fodmap** - fodmap classification of the item. Currently only "low" and "high" are supported
* **category** - food category this item belongs to
* **qty** - (optional) defaults to unlimited. Represents max quanitity to consume while still being considered LOW
* **details** - (optional) contains a subset of the four fodmaps and their quantities. 0 represents LOW, 1 represents MEDIUM and 2 represents HIGH

Notes:

* If you are new to JSON, please note that all food items *except the last item* must have a **comma** after the closing `}`


# Sources: 

In general we only add items that we can successfully crossreference from several different sources. This list below is not exhaustive but contains many of the sources we use.

Keep in mind because the FODMAP diet is relatively new, many foods have not been tested. Most organizations focus on basic foods like apples or potatoes rather than complex meals or ready made products to cover a wide variety of possible combinations.

* http://www.ibsdiets.org/fodmap-diet/fodmap-food-list/
* http://www.ibsdiets.org/wp-content/uploads/2016/03/IBSDiets-FODMAP-chart.pdf
* http://www.katescarlata.com/lowfodmapdietchecklists/
* https://www.dietvsdisease.org/low-fodmaps-food-list/
* http://www.ibsgroup.org/brochures/fodmap-intolerances.pdf
* http://whole30.com/downloads/whole30-shopping-list-FODMAP.pdf
* http://www.arizonadigestivehealth.com/wp-content/uploads/2014/06/FODMAP-diet-for-IBS.pdf
* http://fodmapliving.com/wp-content/uploads/2013/02/Stanford-University-Low-FODMAP-Diet-Handout.pdf
* http://www.rgal.com/wp-content/uploads/sites/11/2013/11/FODMAP-Diet-Chart.pdf
* https://irritablebowelsyndrome.net/ibs-diet/

# Disclaimer

We do not perform any testing ourselves. All compliled data should be used as a guidelines not as a basis of fact.

Consult your physician before beginning any new diet. This general information is not intended to diagnose any medical condition or to replace the advice of your healthcare professional.
