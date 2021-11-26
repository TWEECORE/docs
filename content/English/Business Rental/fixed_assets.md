+++
title = "Asset accounting"
weight = 1040
+++

If you are reading this section, you are most likely dealing with financial and fixed asset accounting in your business. 

In accounting, fixed assets are those assets that are shown on the assets side of a balance sheet and are intended to serve the business operations of a company on a permanent basis. Current assets in companies are all assets that are intended for short-term sale, consumption, processing, further processing or repayment as part of the business process. They are only in the company for a short period of time and, unlike fixed assets, do not serve the business on a permanent basis.

According to this definition, rental items behave like fixed assets, which at the same time have the characteristics of current assets.
 
As a rule, you may not depreciate current assets unless there is a reason to do so.
 
Thus, the most important difference is: an item intended for rental belongs to fixed assets. Consequently, an asset must also be created for it in Business Rental. If you purchase an item that is not for rental, but for direct sale, it is a current asset and the creation of an asset is not necessary.

## Assets in Business Rental

An asset intended for rental is essentially no different from the standard assets that Business Central already uses. As an example, in this section we will create an asset that is also intended for rental.

For our example, we will create a new item. This item will then be converted to a main rental item. For more information on this procedure, see the [Rent Article](https://businessrental.tweecore.de/articles/EN/rent_article.html) section.

![article men's bike](/images/item_new_en.jpg)

Conversion to a main rental article automatically creates a new attachment in the attachments table. 

![Attachment men's bike](/images/fixed_asset_en.jpg)

The various defaults can be set under the Attachments item in the rental setup. If you also do not intend the conversion to a main rental item to create an attachment, you can disable this feature by checking the "Automatically create" box. However, you will then have to create it manually.

![Rent setup attachments](/images/setup_asset_en.jpg)

Let's take a closer look at this attachment and open it. The necessary mandatory fields are indicated with the red asterisk. So enter at least the depreciation start date. If you also fill in the useful life in years, the end date of the useful life will be calculated and filled in.

![Rental equipment assets](/images/asset_rental_en.jpg)

Newly added is now the tab with the area of renting. Here you can see at a glance which article number, main rental article and rental article number this asset represents. Please keep in mind that article and main rental article numbers can appear multiple times in the assets, while the rental article number is only assigned once.
