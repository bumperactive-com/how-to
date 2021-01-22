## PRODUCT CREATION

### Table of Contents

#### B-STYLE STORES (The New Way)
1. [Apparel Items](https://github.com/bumperactive-com/how-to/blob/master/product-creation.md#1-apparel-items)
2. [Non-Apparel Items](https://github.com/bumperactive-com/how-to/blob/master/product-creation.md#2-non-apparel-items)

#### A-STYLE STORES (The Old Way)
3. [Apparel Items](https://github.com/bumperactive-com/how-to/blob/master/product-creation.md#3-apparel-items)
4. [Non-Apparel Items](https://github.com/bumperactive-com/how-to/blob/master/product-creation.md#4-non-apparel-items)

-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

### B-STYLE STORES

-------------------------------------------------------------------------------------

##### *1. APPAREL ITEMS*

- Find a template for the type of product being created.
- Click the three dots to open the dropdown menu and select **Copy**.
![](images/product-creation0.png?raw=true)
- Edit **Product Name** and **SKU**.
![](images/product-creation35.png?raw=true)
- Select relevant product categories, such as Pride, Tee, etc.
![](images/product-creation1.png?raw=true)
- Check product price to ensure cost matches other products of similar type.
- Use Product Description Generator and paste output into product **Description**.
![](images/product-creation36.png?raw=true)
- Upload product images.
![](images/product-creation2.png?raw=true)
- The image with the blue dot will be set as the default product thumbnail. Set as needed.
![](images/product-creation37.png?raw=true)
  + **Save** changes.

- In **Product Identifiers**, edit SKU again.
  + Not sure why this appears twice, just do it.

- Product Options
  + **ALL tees/tanks/hoodies need these five options**:
    - Apparel Brand (**Modifier** option, *created manually*)
    - Apparel Color (**Modifier** option, *created manually*)
    - Apparel Size (**Variant** option, *created by template*)
    - Apparel Style (**Variant** option, *created by template*)
    - Product Type (**Variant** option. *created by template*)

  + **Make sure Apparel Size, Apparel Style and Product Type options each have one value marked as** *Default*.
    - Otherwise, product can't be added to cart.
    - Make sure Apparel Size and Style are set as *Rectangle List*.
    - Make sure Product Type is set as a *Dropdown*.
      + Rectangle options are shown on storefront, Dropdown options are hidden from public view.
      + We don't need customers to see the product type, but we DO need them to pick a damn size!
![](images/product-creation3.png?raw=true)
  + Edit the alphanumeric portion of each variant SKU.
    - If product contains Women's and Unisex options:
        + Each Unisex variant should have same alphanumeric value (eg: 0001)
        + Each Women's variant should have same alphanumeric value (eg: 0002)
![](images/product-creation4.png?raw=true)
    - **Save** after editing SKUs to prevent loss of work.

  + In **Modifier Options**, add **Apparel Brand** and **Apparel Color** options.
    - Make sure **Type** is set as *Dropdown*.
    - Make sure each option is required and the value is marked as *Default*.
      + Otherwise, product can't be added to cart because the customer will not be able to select a required option.

![](images/product-creation5.png?raw=true)
    - **Save** changes.

  + **If everything looks good, the new product is ready for review!**

-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

##### *2. NON-APPAREL ITEMS*
  
- Find an appropriate template.
- Click the three dots to open a dropdown menu and select **Copy**.
![](images/product-creation0.png?raw=true)
- Edit **Product Name** and **SKU**.
![](images/product-creation38.png?raw=true)
- Select relevant product categories, such as Pride, Goods, etc.
![](images/product-creation1.png?raw=true)
- Check product price to ensure cost matches other products of similar type.
- Use Product Description Generator and paste output into product **Description**.
![](images/product-creation36.png?raw=true)

- Upload product images.
![](images/product-creation2.png?raw=true)
- The image with the blue dot will be set as the default product thumbnail. Set as needed.
![](images/product-creation37.png?raw=true)
  + **Save** changes.

- In **Product Identifiers**, edit SKU again.
  + Not sure why this appears twice, just do it.

- ***By default, non-apparel item templates will include the Product Type variant; however, these items do not require variant SKUs. Therefore, the Product Type variant will need to be manually changed to a Modifier Option***.
- From the product edit screen, under Variant Options, select **Configure Options**.
  + Copy the entire text in the **Values** field.
  + Select **Delete Option**. Then select **Save Variants**.
- From the product edit screen, under **Modifier Options**, select **+ Add Modifier Option** and then select **+ Add Modifier Option** again on the following screen.
  + In the **Name** field enter 'Product Type', choose 'Dropdown' in the **Type** field and paste the text you previously copied into the **Values** field.
  + Check the **Default** option and check the **Required** box.
  + Select **Create Options**.
- Save your product by selecting **Save** at the bottom.
- **The new product is now ready for review!**

-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

### A-STYLE STORES

-------------------------------------------------------------------------------------

##### ***3. APPAREL ITEMS***

- Find an appropriate template for the new product.
- Click the three dots to open a dropdown menu and select **Copy**.
![](images/product-creation0.png?raw=true)
- Edit product **Name**.
- Check **Default Price** to ensure cost matches other products of similar type.
- Select relevant product categories, such as Pride, Tee, etc.
- Edit **Product code/SKU**.
- Use Product Description Generator and paste output into product **Description**.
  + **Save** changes.

- Click the **Images & Videos** tab and upload product images into the box below.
![](images/product-creation6.png?raw=true)
- The image with the blue dot will be set as the default product thumbnail. Set as needed.
![](images/product-creation7.png?raw=true)
  + **Save** changes.

- Click the **Options & SKUs** tab.
![](images/product-creation8.png?raw=true)
- See how the assigned option set only includes **Apparel Style**, **Apparel Style**, and **Product Type** options.
  + This means we need to add **Apparel Brand** and **Apparel Color** options.
  + To do this, we need to make a copy of the assigned option set, add the missing options to the new option set and assign it to the new product.
  + Click **Product Options** in the sidebar menu.

![](images/product-creation9.png?raw=true)
  + Click the **Option Sets** tab.

![](images/product-creation10.png?raw=true)
  + Find the option set for the new product and make a copy.
![](images/product-creation11.png?raw=true)
  + Edit the option set **Name**.
    - Remove *Copy of* from the front of the name.
    - Append the new product color to the back of the name.
      + eg: - ATHLETIC BEIGE or - NEON BLACK
![](images/product-creation12.png?raw=true)
  + Search **Available Options** to see if the needed options already exist. If not, they will need to be created.
  + Notice that the **Apparel Color** option for **Athletic Beige** already exists.
  + Notice that the **Apparel Brand** option for this product does **NOT** exist and thus needs to be created.
![](images/product-creation13.png?raw=true)
  + Click **Add** to add the Apparel Color option to our new option set.
![](images/product-creation14.png?raw=true)
  + You should then see the Apparel Color option listed the **Options In This Set** box.
![](images/product-creation15.png?raw=true)
  + Great! Now let's create the missing **Apparel Brand** option.
  + Click **Product Options** in the sidebar menu.

![](images/product-creation9.png?raw=true)
  + In the **Options** tab, click **Create an Option**.

![](images/product-creation16.png?raw=true)
  + Edit the **Option Name** and **Display Name**.
    - **Option Name** is used to differentiate option from other Apparel Brand options.
    - **Display Name** is just the option category (Apparel Brand).

![](images/product-creation17.png?raw=true)
  + Set **Display Type** to *Multiple Choice* and **Display Style** to *Dropdown*.
    - Remember, all options not needed by customer are set to *dropdowns* and then hidden on storefront.
    - Unless the product uses Ladies + Unisex combined, only **Apparel Size** needs to be visible.
      + If the product *does* combine Ladies and Unisex, **Apparel Style** also needs to be visible as a *Rectangle*

![](images/product-creation18.png?raw=true)
  + Set **List of Values**. For Apparel Brand, there should only be one value and it needs to be marked as *Default*.
    - If not marked as *Default*, product will not be able to be added to cart.
    - Use [BRAND] Tee ([GARMENT ID]) Made in USA convention.
      + If needed, specific value can be copied from a similar product on another store.

![](images/product-creation19.png?raw=true)
  + Click **Next**.

![](images/product-creation20.png?raw=true)
  + Assign the new option to the new option set.
    - You can apply the option to multiple option sets if needed.

![](images/product-creation21.png?raw=true)
  + **Save** changes.

  + Now we need to apply the new option set to the new product!
  + Click **View** in the **Products** sidebar.

![](images/product-creation22.png?raw=true)
  + Open the new product.
  + In the **Option Set** dropdown, select the newly-created option set to apply it to the new product.

![](images/product-creation23.png?raw=true)
  + There should now be five options in the list, as seen below.

![](images/product-creation27.png?raw=true)
  + **Save** changes.

  + Click the link in the green banner to view the new product as it will appear on the storefront.

![](images/product-creation24.png?raw=true)
  + Make sure the **Apparel Size** option is visible on the storefront.
  + Make sure the **Apparel Style** option is visible if needed, hidden if not.
  + Make sure the **Apparel Brand**, **Apparel Color** and **Product Type** options are *NOT* visible on the storefront.
  + If everything looks good, we are ready to create some SKUs!

  + Navigate to **Products** > **View**.

![](images/product-creation22.png?raw=true)
  + Open the new product and click the **Options & SKUs** tab.
![](images/product-creation27.png?raw=true)
  + Click the **SKUs** tab and then click the **Create a SKU** button.
![](images/product-creation28.png?raw=true)
  + In the **SKU** field, enter the first variant SKU.
![](images/product-creation29.png?raw=true)
  + Mark relevant values for this particular variant.
  + Each option needs a marked value.
![](images/product-creation30.png?raw=true)
  + Once all variant-specific options are set, click **Save and Close**.
  + You should now see the newly-created variant SKU with all five options attached.
    - **Save** changes.

![](images/product-creation31.png?raw=true)
  + Repeat this process until each available size has its own Variant SKU.
  + To save time, copy the SKU you just created and change the values.
![](images/product-creation32.png?raw=true)
  + In this example, change the SKU from **ABCD-TEE-0001-XS** to **ABCD-TEE-0001-S**
    - Also change the **Apparel Size** value from **XS** to **S**.
![](images/product-creation33.png?raw=true)
  + Once each available size has its own Variant SKU, **save** changes.
![](images/product-creation34.png?raw=true)
  + **The new product is now ready for review!**

-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

##### ***4. NON-APPAREL ITEMS***

- Find an appropriate template for the new product.
- Click the three dots to open a dropdown menu and select **Copy**.
![](images/product-creation0.png?raw=true)
- Edit product **Name**.
- Check **Default Price** to ensure cost matches other products of similar type.
- Select relevant product categories, such as Goods, Stickers, etc.
- Edit **Product code/SKU**.
- Use Product Description Generator and paste output into product **Description**.
  + **Save** changes.

- Click the **Images & Videos** tab and upload product images into the box below.
![](images/product-creation6.png?raw=true)
- The image with the blue dot will be set as the default product thumbnail. Set as needed.
![](images/product-creation7.png?raw=true)
  + **Save** changes.

- Click the **Options & SKUs** tab.
- See how the assigned option set includes a **Product Type** option.
![](images/product-creation25.png?raw=true)
  + This is the only option needed for Non-Apparel Items.
  + Click the **Option Name** (Product Type) to view the option.

![](images/product-creation26.png?raw=true)
  + Make sure the option is set as a *Dropdown* since it will be hidden from customers.
  + Make sure the option value is marked as *Default*.
    - Otherwise, product cannot be added to cart because the customer will not be able to select a required option.
  + If the option looks good, you can cancel out. If not, make necessary changes and click **Save**.
  + **The new product is now ready for review!**

