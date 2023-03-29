# Commerce API Postman Collection
Welcome to the demo of the Commerce API! You can use this Postman collection to test our API offering, string together cart flows, and make calls to a test environment with a test API key provided to you by Digital River.
## Documentation
You can find documentation for the Commerce API suite on our Doc Portal here: [https://docs.digitalriver.com/commerce-api](https://docs.digitalriver.com/commerce-api)

# Installation and Use
To install the API Demo, click the **Run in Postman** button below and select **Postman for Windows**:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.postman.com/digital-river-doc-team/workspace/commerce-api/collection/22793802-b8abd429-d3f6-4594-adc2-f7adaa1f09ac?action=share&creator=22793802)

Alternatively, you can install this collection from your Postman client by directly downloading the JSON file, opening Postman, clicking **Import**, dragging the JSON file to the Import window, and clicking **Import in the Import** window.

## Step 1: Obtain API credentials
Before you can start sending Commerce API requests, use the [Request Demo](https://www.digitalriver.com/request-demo/) form to start the site creation process and request your [API keys](https://docs.digitalriver.com/commerce-api/resources/API-structure/api-keys) or contact your Customer Success Manager.

* To access Commerce API on a trial basis, state that you need a "test API key for the Commerce API suite."
* To access the Shopper APIs and the Admin APIs collections, state that your "keys need permission to use both the Shopper APIs and the Admin APIs."

Digital River will reach out to you with more information. If you already have a Commerce API account, you can use your secret key to begin making API calls as well.

Digital River uses these keys to [authenticate](https://docs.digitalriver.com/commerce-api/shopper-apis/oauth/authentication) your API requests. The API key you use to authenticate the request determines whether the request is in live mode or test mode. If you forget to provide your key or use an incorrect or outdated key, the API returns an error.

## Step 2: Perform a test request
After you obtain your API keys, you'll want to perform some test requests. The following steps demonstrate how to do this:

**Important**: Make sure you [install Postman](https://www.postman.com/downloads/) before proceeding.

Complete the following steps:

1. Click the **View more actions** (...) icon on the Commerce API Quick Start collection you just imported and select **Edit**.
2. In the **Edit Collection** window, select **Variables**.
3. Using the **Current Value** fields, enter the appropriate API key for each variable, and click **Update**.

  * **apiDomain**: For the production environment, enter `api.digitalriver.com`. For the client test environment (CTE) enter `api-cte-ext.digitalriver.com`.
  * **publicApiKey**: Provide the public API key provided by Digital River.
  * **drjsApiKey**: Provide the DigitalRiver.js key provided by Digital River.
  * **confidentialApiKey**: Provide the confidential API key provided by Digital River.
  * **confidentialSecret**: Provide the confidential secret provided by Digital River.
4. Once you set up the variables, run each request individually or use the [collection runner](https://learning.postman.com/docs/collections/running-collections/intro-to-collection-runs/) to run each request sequentially.

Now that you've successfully performed a series of simple test requests, you're ready to take a deeper dive into the Commerce API.

# Contact Us
If you have questions or concerns or if you want to move forward with Digital River, please visit our website at https://www.digitalriver.com/ and click **Talk to Sales**.
