+++
title = "Creating itmems, main rental itmes and rental itmes."
weight = 1020
+++

To rent out an item, you need a main rental item and a rental item that references the main rental item. To create a rental item, call up the list of items that you already know from the standard system.

Create a new item here that you want to rent out. Depending on the template, certain values may already be filled in, such as the product booking group. If this is not the case, please make a selection here. You can recognize mandatory fields by a red asterisk. If you do not make a selection, you will not be able to continue and will receive a corresponding message. 

The item must have a stock, you can buy it regularly or transfer it to your stock via the item journal to your warehouse. Using the Convert item to rental item function, you create a so-called main rental item and at the same time the desired selection of rental items. You can convert at least one or at most the entire stock to a rental item.

For example, let's assume that you are a bicycle dealer. This may mean that you want to both rent and sell a certain type of bicycle. For the sale, nothing changes for you, you can use the usual standard sales process here and thus you don't need a main rental item either. For our example, you want to rent out a certain type of bike as well as sell it. So you create a new item and post a corresponding stock. 

Now you use the convert function:

![convert function](/images/change_main_en.jpg)

You will be asked if you are sure you want to do the conversion. Confirm this with Yes. You will be asked how many of the existing items you would like to convert to a rental item, and the complete stock will be suggested. In our example, we want to create 15 of the 50 available trekking bikes as rental items. After the conversion is done, let's take a look at the item items:

![item items](/images/ledger.jpg)

As you can see, 50 items were purchased regularly. Then there was a retirement posting on the 15 items that have now been converted to a rental item. In the rental items view, we find these 15 bikes again:

![rentalitem](/images/rental_item_en.jpg)

In case you want to convert a rental item back to regular inventory (merchandise), you can convert a rental item back to an item at any time, provided the rental item is not currently in rental.

![Convert rental item to item](/images/convert_rent_item_en.jpg)

So the logic can be summarized as follows: any item you want to rent, convert it to a main rental item. You can manage as many rental items in your system as you want.

![Logic of rental items](/images/chart_en.jpg)

Main rental items are of type always **without stock** and base unit piece. With the posting details you define which G/L accounts are to be posted to and addressed during the rental. If no setup has been made yet, please consult your financial accounting department. 

The main rental item fulfills the function of a superior item that you want to rent out. In other words, you always have at least one **main** rental item, but this can be present as often as you want as a rental item. The rental item is also the product you rent to the customer. You cannot rent out a main rental item.

If you want, you can enter values on the main rental item card under Prices & Discounts. 

![Rental prices](/images/rental_prices_en.jpg)

These can be stored in a price list for specific customers, price groups or campaigns. As an example you can see a price list for the two main rental items trekking bike and mountain bike, these prices are valid for all customers. To activate the price list you have to change the status from Draft to Active.

![Price list](/images/price_list_en.jpg)

Basically, the creation is now complete and you can offer and rent rental items. Now you still need to make sure that you provide details about your billing periods and different rental calendars, if applicable.