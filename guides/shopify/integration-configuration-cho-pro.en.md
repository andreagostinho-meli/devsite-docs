# Checkout Pro

When installing [Checkout Pro](/developers/en/docs/checkout-pro/landing), there may be an **increase in the approval rate of online store sales**. This happens because buyers will be able to pay using a Mercado Pago account and the entire purchase process will be done in our environment, which facilitates payment. At the end of the transaction, these buyers are redirected to the store environment.

----[mlb]----
To configure Checkout Pro in a Shopify store, follow the steps below:

1. Go to your [Shopify](https://accounts.shopify.com/store-login) store.
2. In the store's administrative panel, click on **Settings**.
3. Once there, select the **Payments** option. Then, click on the **Choose a provider** button.
4. Type Mercado Pago in the search bar. Once you find it, select it as your payment method.
5. Enter your **production credentials** (`Client_id` and `Client_secret`) in the fields that require them. Remember to keep your [credentials](/developers/en/docs/shopify/additional-content/your-integrations/credentials) handy.
6. In the next step, you will be able to select the images of the payment methods you want to display in the store. **Important: these images are for illustrative purposes only and do not imply the activation of the payment method selected**.
7. Lastly, the store will offer you the option to **Enable test mode**. By activating this option, orders completed with Checkout Pro **will not be real orders**. That is, they will be test orders that, even if completed, will not have their status updated on the platform and will not appear on the Mercado Pago panel in the seller's account.
8. To finish, click on **Activate Mercado Pago**. 
 
> In case of renewing your credentials, remember to replace both the production and test credentials in your integration.

------------
----[mla, mlm, mpe, mco, mlu, mlc]----
> WARNING
>
> Attention
>
> If you are using the old Mercado Pago app ("Mercado Pago"), [click here](/developers/en/docs/shopify/how-tos/migration) to find out how to migrate to the current version ("Checkout Mercado Pago" ).

To install Checkout Pro in a Shopify store, follow the steps below:

1. Go to your [Shopify](https://accounts.shopify.com/store-login) store.
2. In the store's administrative panel, click on **Settings**.
3. Once there, select the **Payments** option. 
4. In "Additional payment methods", click on the **Add payment methods** option.
5. Go to the **Search by provider** tab and look for the new app with the name "Checkout Mercado Pago".
6. Once you have found it, select it and click **Activate** and then **Connect**.
7. Select **Install App** and then **Manage**.
8. Put your **production credentials** (`public key` and `access token`) in the fields that request it and click **Save**. Remember to keep your [credentials](/developers/en/docs/shopify/additional-content/your-integrations/credentials) handy.
9. To finish the installation, select **Activate Checkout Mercado Pago**.

> In this step, you can select the images of the means of payment that you want to show in your store for illustrative purposes. Also, if you wish, you can enable [test mode.](/developers/en/docs/shopify/sales-processing/integration-test)
> <br/><br/>
> In case of renewing your credentials, remember to replace both the production and test credentials in your integration.

------------