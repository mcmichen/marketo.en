---
unique-page-id: 11378812
description: Discover Accounts - Marketo Docs - Product Documentation
title: Discover Accounts
---

# Discover Accounts {#discover-accounts}

Discover Accounts - Marketo Docs - Product Documentation

Use the Discover option to identify potential target accounts.

### What's in this article? {#what-s-in-this-article}

[Discover CRM Accounts](#discoveraccounts-discovercrmaccounts)  
[Discover Marketo Companies](#discoveraccounts-discovermarketocompanies)

#### Discover CRM Accounts {#discoveraccounts-discovercrmaccounts}

Identify potential target accounts from your CRM.

>[!NOTE]
>
>After you connect your CRM to Marketo ABM, **Discover CRM Accounts** will show all the CRM accounts and relevant information to help you choose the right named accounts. Marketo adds additional information on top of what's received from the CRM.

**People **(In Discover CRM Accounts & Discover Marketo Companies): Includes both Contacts and Leads. Leads can be discovered using Marketo's [lead-to-account matching](http://docs.marketo.com/display/DOCS/Lead+to+Account+Matching).  **Potential People** (In Discover CRM Accounts & Discover Marketo Companies): Shows how many leads Marketo found that could possibly belong to a CRM account.

**Custom CRM field **(In Discover CRM Accounts only): This will help you align your sales and marketing organization for selection of correct target accounts. Once you [map the custom CRM field](http://docs.marketo.com/x/1wnG) with Marketo ABM, we’ll show you the mapped data to help you identify your target accounts.

##### 1. In Named Accounts, click the New drop-down and select Discover CRM Accounts. {#discoveraccounts-innamedaccounts-clickthenewdrop-downandselectdiscovercrmaccounts.}

![](assets/disc-crm-one.png)

##### 2. A new window/tab will open. Select the CRM account(s) you want to add to your Named Accounts and click Next. {#discoveraccounts-anewwindow/tabwillopen.selectthecrmaccount(s)youwanttoaddtoyournamedaccountsandclicknext.}

![](assets/disc-crm-two.png)

##### 3. The preview screen confirms your amount of selections. Click Create. {#discoveraccounts-thepreviewscreenconfirmsyouramountofselections.clickcreate.}

![](assets/disc-three.png)

That's all there is to it!

![](assets/disc-four.png)

#### Discover Marketo Companies {#discoveraccounts-discovermarketocompanies}

Identify the right companies for targeting.

>[!NOTE]
>
>In Discover Marketo Companies, you will see Marketo companies that didn't come from your CRM.

##### 1. In Named Accounts, click the New drop-down and select Discover Marketo Companies. {#discoveraccounts-innamedaccounts-clickthenewdrop-downandselectdiscovermarketocompanies.}

![](assets/one-1.png)

##### 2. A new window/tab will open. Select the companies you want to add to your Named Accounts and click Next. {#discoveraccounts-anewwindow/tabwillopen.selectthecompaniesyouwanttoaddtoyournamedaccountsandclicknext.}

![](assets/disc-comp-two.png)

>[!NOTE]
>
>In Discover Marketo Companies and Discover CRM, Marketo automatically:
>
>* Finds people from your Marketo database that have that company listed in their record. If you see multiple values for some of the attributes (e.g. Industry), it's because Marketo found different values listed for those individual people. The attribute with the most hits wins
>
>In **Discover CRM **only, Marketo automatically:
>
>* Syncs and associates CRM Contacts with the Named Account
>
>In **Discover Marketo Companies** only, Marketo automatically:
>
>* Filters out most Internet Service Providers and Public Domains (e.g. [Yahoo.com](http://Yahoo.com), [Gmail.com](http://Gmail.com)) as company names
>
>* Dedupes CRM accounts. If you have "Acme" in one record and "Acme Inc" (or any of the following suffixes: Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), we will merge them in ABM as just "Acme"
>
>If you'd like Marketo to de-dupe accounts by CRM ID or Account Owner instead of by Company Name, please contact [Marketo Support](http://docs.marketo.com/cdn-cgi/l/email-protection#1c6f696c6c736e685c717d6e77796873327f7371).

##### 3. Click the down arrow under the Named Account column to reveal the drop-down. {#discoveraccounts-clickthedownarrowunderthenamedaccountcolumntorevealthedrop-down.}

![](assets/disc-comp-three.png)

>[!CAUTION]
>
>Going forward, any new people from these selected companies will automatically be assigned to their respective named accounts. Please double-check these companies and make sure they are assigned to the correct Named Account.

##### 4. To select an existing Account, click the Named Account drop-down, choose the desired account, then click Next. {#discoveraccounts-toselectanexistingaccount-clickthenamedaccountdrop-down-choosethedesiredaccount-thenclicknext.}

![](assets/disc-comp-four.png)

You also have the option of creating a new Named Account by typing the desired name directly in the drop-down box. Click away from the box when done...

![](assets/disc-comp-five.png)

...and you'll see your new Named Account. At that point just click **Next** like in Step 4.

![](assets/disc-comp-six.png)

##### 5. Click Create. {#discoveraccounts-clickcreate.}

![](assets/disc-comp-seven.png)

Nice work!

![](assets/disc-co-six.png)

>[!NOTE]
>
>**Explanation**
>
>If you're seeing a mismatch between CRM accounts you've selected and what's in the Discover CRM Grid, it's likely due to one or more of the following:
>
>* Having different CRM accounts with similar names that got de-duped
>* The next scheduled sync hasn't occurred yet
>

>[!NOTE]
>
>**Related Articles**
>
>* [Lead to Account Matching](discover-accounts/lead-to-account-matching.md)
>
