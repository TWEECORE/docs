+++
title = "Rental calendars and billing periods."
weight = 1050
+++

Setting up different rental calendars is necessary whenever you work with different rental rates. For example, for a rental rate that includes weekend billing, you need to create a rental rate and a calendar that allows this billing method. However, you can also configure a monthly flat rate where the price is always the same and it does not matter whether the month has 28 or 31 days.

![Rent tariff](/images/rental_rates_en.jpg)

### Example of a day-based billing without calculation of weekends and holidays:

Create a new rental tariff for this purpose. This should be named in such a way that users immediately recognize what kind of constellation it is. For our example, this means that we create a rental rate DAY. From the rental rate type, you now select daily basis and you can select the default rental calendar DE (The default rental calendar DE should already include the holidays and weekends, if necessary you should check this again). In the field for the date formula please enter 1D. BusinessRental will now recognize that holidays and weekends should not be calculated. 

### Example of a monthly flat rate

Create a new rental rate. For a flat rate it is relevant that the rental rate type contains the value Flat rate. Quantity in days must be 0, the date formula for the flat rate must be filled with 1M. The rental calendar is not relevant here, since the customer is charged a flat monthly rate and holidays are not taken into account.

### Example of daily calculation with holidays

If you want holidays to be charged, you control this through the various rental calendars. As an example, you can calculate 12/25 (it is a federal holiday, after all) by unchecking "Free" in the rental calendar on that day. BusinessRental will then calculate the day regularly. However, please keep in mind that it makes sense to create a separate calendar for this scenario, as the default calendar has numerous holidays and weekends stored.

### Invoicing period

You can determine yourself over which period the billing will extend. Usually, billing is done monthly, but you can also bill every 14 days or weekly. Create a new billing period and store an appropriate date formula (14D for 14 days or 1M for a month) and delimit the period. You can choose to settle on the first day of the period, a fixed day, or the last day of the period.

![Rent statement](/images/invoicing_period_en.jpg)