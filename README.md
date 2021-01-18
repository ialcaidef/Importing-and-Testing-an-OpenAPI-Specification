# Importing-and-Testing-an-OpenAPI-Specification

### Importing and Testing an OpenAPI Specification

#### Demonstration Steps

1. Open Microsoft Edge.

2. Navigate to **https://portal.azure.com**.

3. If a page appears asking for your email address, enter your email address, click **Next**, enter your password, and then click **Sign In**.

4. If the **Stay signed in?** dialog box appears, click **Yes**.

   >**Note**: During the sign-in process, if a page appears prompting you to choose from a list of previously used accounts, select the account that you previously used, and then continue to provide your credentials.

5. On the menu in the panel on the left side, click **Create a resource**.

6. In the **Search** box, type **API management**, click **Enter**, and then click **Create**.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/01.png)

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/02.png)

7. In the **API Management service** page, enter the following details:

   - Name: **Mod6demo5**{YourInitials}
   - Resource Group:
     - Select **Create new**.
     - Type **Mod6Demo5ResourceGroup**.
   - Organization name: Enter the name of your organization
   - Click **Create**

8. Wait until the API Management instance is created.

9. Click **All resources**, and then click on the new **API Management** section that was created.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/03.png)

10. Under the **API MANAGEMENT** section, click **APIs**.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/04.png)

11. Click **OpenAPI Specification**, and then enter the following details:

    - In **OpenAPI Specification** box, paste the following URL: **http://conferenceapi.azurewebsites.net/?format=json**

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/05.png)

    > **Note**: The following URL is a Swagger JSON API that was provided by Microsoft and hosted on Microsoft Azure.

    - In **Products**, select **Unlimited**.
    - Click **Create**.

12. In the **All APIs** section, click **Demo Conference API**.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/06.png)

13. Click the **Test** tab, then click **GetSessions**.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/07.png)

14. Click **Send**, and check that the response is **200** with a collection of sessions.

![20487D_Images](https://github.com/ialcaidef/Importing-and-Testing-an-OpenAPI-Specification/blob/main/Images/08.png)

15. Click **GetSession**, then inside the **value** box, type **100**;

16. Click **Send**, and check that the response is **200** with session data.
