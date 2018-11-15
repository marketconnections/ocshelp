---
description: Connect OCS to WiseAgent and take the work out of managing your mailing list.
---

# WiseAgent CRM Integration

### How it works <a id="how-it-works"></a>

Sign up to use the [WiseAgent](https://www.thewiseagent.com/info.asp) CRM \(you can try it free\). Manage all your Contacts in the CRM \(schedule meetings, send emails and so on\). Create a Category called "Realty Report". Assign this category to contacts who should get a Realty Report newsletter. 

Set up with Market Connections for [Realty Report](http://www.marketconnections.com/realty/realtyreport.php). Then, give us an API Key to your Wise Agent account.

Every month, we will automatically synchronize the Realty Report Mailing List with your WiseAgent Contacts. The contacts you assigned to the "Realty Report" category will automatically receive the newsletter. 

If you update or delete Contacts at WiseAgent, the information automatically syncs to us when we mail your newsletters.

You can even customize individual contacts so that they get different versions of the newsletter.

We will bill you monthly \(or however often you've setup to get the newsletter\) for the number of Contacts in your "Realty Report" category. You can adjust the number of recipients by adding or removing the category from your Contacts. Each one of your Contacts will get a customized newsletter mailed directly to their address.

There's no extra charge for WiseAgent Integration with Market Connections, just less hassle.

### Get Started <a id="get-started"></a>

To integrate with WiseAgent CRM, we need you to login to your account and retrieve a valid API Key. This allows us to "hook up" your Market Connections Mailing List to your WiseAgent Contacts. 

#### Watch the How-To Video: <a id="watch-the-how-to-video"></a>

{% embed url="https://player.vimeo.com/video/184373372" %}

**NOTE:** The API key will allow Market Connections to perform the following functions on your account:

* Retrieve all your Contact Categories
* Retrieve all your Contact mailing data, including names and addresses of all your Contacts
* Add notes to your Contacts \(we will add a note that we mailed your newsletter\) _If you are not comfortable with Market Connections having this access to your data, you should not give us your API Key._

#### Integration Overview <a id="integration-overview"></a>

Setting up integration is a 3 step process:

1. Retrieve your API Key
2. Choose the WiseAgent Contacts who should get the newsletter
3. Choose the default version of the Newsletter you want your recipients to get. ![](https://marketconnections.gitbooks.io/ocs3help/content/v/071549b37967e0963bc353d63fc707ad9f08d327/Images/WiseAgent%20Integration%20Step1.png)

#### How to retrieve your API Key <a id="how-to-retrieve-your-api-key"></a>

To retrieve your WiseAgent API Key:

1. Login to WiseAgent
2. Select "Integrations Menu" from the profile Welcome Menu at the top right of the WiseAgent screen
3. Click the Lead Management tab
4. Scroll to the bottom of this tab to the API section
5. If you have already given out the API key to other services, click the Add another Key button. This ensures that only Market Connections will use the API Key.
6. Copy the contents of "Key" field

![](https://marketconnections.gitbooks.io/ocs3help/content/v/071549b37967e0963bc353d63fc707ad9f08d327/Images/WiseAgent%20Integration%20Step2.png)

It's important that Market Connections has it's own key that you do not assign to anyone else. If you ever want to revoke Market Connections' access to your Contacts, you can do so by deleting this API key. Similarly, if you need to revoke another company's access to your WiseAgent data, doing so won't affect us.

