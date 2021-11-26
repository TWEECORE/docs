+++
title = "Create rental contract"
weight = 1070
+++

There are three ways to create a lease. You can create a new rent contract by hand. 

![Rental agreement ne](/images/mv_new_en.jpg)

Or you can use the function from the rental offer and convert a rental offer into a rental agreement. 

![Convert offer to rental agreement](/images/copy_en.jpg)

If a similar document already exists, copy an existing rental related document. very similar possibility you already know from the standard.

![Copy rental document](/images/copy2_en.jpg)

To map the whole process, in our example we create a rental agreement without the copy function or the conversion via a rental offer.

After you create a new lease, you fill in the customer number, set the lease start and end dates. You will also need a rental rate and billing period. For our example we take a monthly flat rate.

![rental agreement header](/images/mvhead_en.jpg)

Because of the price list, we find a rental item in the lines at a price of 12.50. Remember that you still have the option to enter different prices or discounts here. 

![Rental lines](/images/rent_lines_es.jpg)

Below the lines you will see a summation of the total prices net, gross and granted discounts. 

Compared to your standard sales items, there is no selection of a storage location for rentals. So the field with the storage location code must remain empty. When you are satisfied with the entries, you can release the rental agreement. Now you need to deliver the rental item. To do this, you will find the Book button in the top bar. After selecting it, you will be asked if you want to Deliver, Invoice or Deliver and Invoice. Please select Deliver.

![Deliver lease](/images/ship.jpg)

After selecting with OK the rental item is delivered. 

Before we get to the items, let's take a closer look at the rental delivery, via Navigate you can view the document:

![Rental delivery](/images/shipment_en.jpg)

In the rental delivery you can trace to whom the shipment has gone or print the receipt. Alternatively, by the way, you can use the info box in the right pane to navigate to the documents that are assigned to the named customer. Note, however, that the filtering here is not on the rental agreement, but on the customer, so you may find information on other rental agreements.

![Rental delivery infobox](/images/ship1_en.jpg)

What does the delivery now mean for the items? Let's take a look at the main rental item: SCREENSHOT CONSISTED

To be able to invoice the rental agreement, use the Book button again and select the Invoice item. Please confirm with OK to generate a rental invoice. Depending on the configuration in the rental setup, an unposted or posted rental invoice will now be generated, which you can view and process further on request (print, mail dispatch).

To shorten the process you can also select Deliver and Invoice in the selection and thus create the delivery and invoice at the same time. 

![Navigate rental invoice](/images/invoices_en.jpg)

For direct access, you can view the rental invoices associated with the rental agreement using Navigate. Alternatively, use the info box in the right pane with the familiar alternative assignment. 

With the delivery and the calculation, the rental agreement is now basically completed. It must now be finally ensured that you pick up the rental item again. For this purpose, please create a return via the corresponding button. 

![Navigate rental return](/images/return_en.jpg)

When asked, please select Yes to be able to open the take-back page and enter further information. The posting date in the takeback is automatically populated, but you can customize it. To post a return correctly, you must enter a value in the Return Quantity column in the rows. In our example, this is ONE bicycle. Since rental items can be multiple, but they are always assigned a unique number, you cannot enter any number other than 1 here.

In the rental lines you can see that after posting the return the corresponding values have changed. 

So the processing is finished with this simple example and we can now deal with a more complex rental agreement.

## Rental agreement with shipping costs and daily calculation ##

In this example we will look at how to use Business Rental to map a daily billing as well as the costs for a delivery and pickup. 
For daily billing, we select the rental price code TAG in the rental header or the rental price stored in your system that is configured daily.

![Rental price type](/images/dainly_en.jpg)

Depending on the stored base calendar, a calculation is made on the weekend or not. For our example with the bicycle, a calculation on the weekend is desired, which is why the rental rate DAY is correct.

In the lines we find a total of three lines: a rental item (here a trecking bicycle) as well as two lines for the delivery and the collection. 

![Rental agreement with freight](/images/rentlines_en.jpg)

The objective is as follows: we would like to calculate the costs with the delivery, as well as by the day the renting of the bicycle. The individual days should also be calculated individually (so far we have made a lump sum settlement), at the end we want to calculate the costs for the pickup.

To make this calculation now, we will proceed as follows:
- the wheel as well as the delivery are filled with quantity to deliver 1 (preassignment is usually done automatically).
- the quantity to deliver in the line of the collection is set to 0, thus the calculation basis is missing (since no delivery took place yet).

![Post rental agreement](/images/rentlines_en2.jpg)

- The rental agreement is now ready for invoicing and can be posted. With this you create a posted rental invoice. You can view the amounts via the posting preview for control purposes and then do not generate a posting.

![Book rental agreement](/images/posting_en.jpg)

- after one week we would like to create the second rent invoice, for this please use the function post again. However, make sure that the quantity to deliver in the collection is set to 0.
- On the last day of the rental, the quantity to deliver is set to 1 in the collection resource.
- With the calculation of the collection, the lease is completed.
- Depending on the accounting period used, the number of rental invoices created can vary. In our example we have chosen a weekly billing and therefore we will receive two rental invoices (14 days rented) and one rental invoice for the cost of collection.
- If other billing periods are necessary, these can be created flexibly in the billing periods.

To ensure that all documents belonging to this rental agreement can be found quickly, you can view all previously created rental deliveries and rental invoices under the tab Belonging > Documents. Alternatively, it is possible to use the info box on the right (green frame in the screenshot) to call up the corresponding documents, but the documents assigned to the *customer* can be found here. So if there is or was a second rental agreement for the customer, the relevant information can be retrieved here.

![view rental vouchers](/images/overview_en.jpg)

## Automatic Rental Extension

