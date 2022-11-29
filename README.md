# github.io

<?xml version="1.0" encoding="utf-8" ?>
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <meta name="generator" content="Adobe RoboHelp 2022" />
  <title>Overview</title>
  <meta name="topic-status" content="In Progress" />
  <link rel="stylesheet" type="text/css" href="../../assets/css/as_stylesheet.css" />
</head>
<body>
  <h1 class="POS-Numbering11-Bilby-3">Overview</h1>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2">welcome</h1>
  <h3 class="POS-H3-BlueTonguedSkink">What Is Posi Giving Essentials (PGE)?</h3>
  <p lang="EN-US" paraeid="{a4cdf12e-3f91-423e-a6ae-4915d670e09f}{162}" paraid="1724497254" xml:lang="EN-US">PGE is a mini version of Posimente Posi Giving. It does a lot of the same work but has reduced functionality.</p>
  <p lang="EN-US" paraeid="{a4cdf12e-3f91-423e-a6ae-4915d670e09f}{162}" paraid="1724497254" xml:lang="EN-US"> </p>
  <p lang="EN-US" paraeid="{a4cdf12e-3f91-423e-a6ae-4915d670e09f}{162}" paraid="1724497254" xml:lang="EN-US">PGE is a great fit for a school or any other organisation that wants to manage basic fundraising. You can at any point extend the base functionality to include payment processing, receipting and additional campaign management features by adding Posimente ProntoPayments and ProntoEngage. PGE can be used as a standalone app in your Salesforce org, with no additional dependent packages required. It will just work. It can also be inserted into the Posimente education management system, Posi Ed, with or without the addition of ProntoPayments and Pronto Engage.</p>
  <h3 class="POS-H3-BlueTonguedSkink">ProntoPayments And Pronto Engage</h3>
  <p>ProntoPayments is an enterprise-grade payment processing package which can be installed in any Salesforce org. It provides end-to-end payment management, including being able to insert a Pay Now button into any Salesforce object where you want to immediately process a contact payment, to secure payment gateways where the payment transaction takes place.  </p>
  <p> </p>
  <p>ProntoEngage is a bulk Lead to Campaign import tool. ProntoEngage will check whether the Lead or Contact already exists in Salesforce based on certain criteria, and if not, create a new Lead and add it to a campaign. When creating an Opportunity from a Campaign, Salesforce Nonprofit Cloud does not automatically copy the Campaign information to the New Opportunity. ProntoEngage provides an auto-mapping functionality.</p>
  <p> </p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 1;">Who would Choose PGE over posi giving</h1>
  <ul class="Square">
    <li>A school that wants to add fundraising capabilities to its school management</li>
    <li>A school that wants to a diverse catalogue of fundraising products</li>
    <li>An organisation that doesn&#39;t manage recurring donations or subscriptions</li>
    <li>An organisation that already has payment processing, receipting and donor management systems in place, but is looking to add or improve its fundraising capabilities</li>
    <li>An organisation that already has a system and process for publishing web page donation pages</li>
  </ul>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 2;">inclusions and exclusions</h1>
  <h3 class="POS-H3-BlueTonguedSkink">Inclusions</h3>
  <p>The core functionality of PGE includes:</p>
  <ul class="Square">
    <li>Campaigns</li>
    <li>Contacts</li>
    <li>Accounts</li>
    <li>Opportunities</li>
    <li>Funding Projects (Custom Object)</li>
    <li>Dashboards</li>
    <li>Products</li>
    <li>Opportunity Products</li>
    <li>Price Books</li>
  </ul>
  <p>Of these, only Funding Projects is a custom object (created by Posimente). The remaining are standard Salesforce objects. Functionality has been extended in some standard objects with custom fields, to make relationships between objects logical and meaningful.</p>
  <h3 class="POS-H3-BlueTonguedSkink">Exclusions</h3>
  <p>As PGE is a scaled-down version of Posi Giving, it doesn&#39;t include:</p>
  <ul class="Square">
    <li>Quick Donate</li>
    <li>Batch Donation Entry</li>
    <li>Recurring Donations</li>
    <li>Reconciliation</li>
    <li>Return Mail Entry</li>
    <li>Receipt Downloads</li>
    <li>Bulk Data Import Facility</li>
    <li>Donation Pages</li>
    <li>Payment Gateways</li>
  </ul>
  <p>If you are reading this overview to gain a sense of which product is better suited to your organisation&#39;s needs, PGE or Posi Giving, it&#39;s good to consider the exclusions as a way of gauging your requirements. </p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 3;">campaigns</h1>
  <p> PGE campaigns are standard campaigns which can events, appeals or projects and which have a start and end date. For example, &#39;Class Reunion&#39; could be a campaign event to invite contacts to a school reunion with fellow alumni. You add members to Class Reunion the same way you would to any other Salesforce campaign. The difference though with a PGE campaign is that it may not have any opportunities directly linked to it. Instead, the opportunities might be linked to a Funding Project record, which in turn is related to the campaign.</p>
  <p> </p>
  <p>In PGE, the initial campaign is referred to as the Primary Campaign Source</p>
  <figure>
    <figcaption>Opportunity With Primary Campaign Source</figcaption>
    <img class="Posi-Image-Width-400px-With-Border" src="../../assets/images/opportunity_primary_source_campaign.png" />
  </figure>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 4;">Opportunities</h1>
  <h3 class="POS-H3-BlueTonguedSkink">Record Types</h3>
  <p>n PGE, you create new opportunities from these record types:</p>
  <ul class="Square">
    <li>Donation: a donation gift</li>
    <li>Bequest: a posthumous donation gift</li>
    <li>Corporate Partnership</li>
    <li>Grant:</li>
    <li>Invoice:</li>
    <li>Major Gift: a standard major donation gift</li>
    <li>Opportunity Group (OG): a parent opportunity used to group child opportunities when a donor wants to spread their major gift across multiple opportunity products</li>
    <li>Fee Donation:</li>
  </ul>
  <p>Of these types of opportunities, OG is most unique. OG opportunities are similar to parent campaigns in their logical use. A parent campaign has child campaigns associated with it. An OG is used as a parent to link child opportunities. Another comparison is how a computer system using folders and sub-folders. One possible application of using an OG is when a major donor wants to contribute a large donation and asks your organisation what programs you are raising funds for. You might have five programs running which the donor would like to spread their gift across. In which case, you would apply percentages of the gift to Opportunity Products across all five programs.</p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 5;">Products</h1>
  <h3 class="POS-H3-BlueTonguedSkink">What Makes Up A Product?</h3>
  <p>Product is a standard Salesforce object used to create items which donors can choose from to pay for within an opportunity.  Products can be tangible or intangible. Products always belong to a product family and to a price book. If they don&#39;t exist in a price book, they can&#39;t be offered as Opportunity Products. In addition a name, description and a family, products can have the following attributes: </p>
  <ul class="Square">
    <li>Product Code</li>
    <li>Tax Deductible</li>
    <li>Tax Rate</li>
    <li>External ID</li>
    <li>General Ledger (GL) Code</li>
    <li>Product SKU</li>
    <li>Funding Project (Lookup)</li>
  </ul>
  <p>Some of these fields can be matched with your accounting system codes, for reporting, taxes, etc. For instance, if your organisation has a charitable status and a product qualifies for tax deduction, you tick the box for this product.</p>
  <p> </p>
  <p>Product Families can be whatever you need them to be. Here are few possibilities:</p>
  <ul class="Square">
    <li>Donation</li>
    <li>Tuition</li>
    <li>Books</li>
    <li>Uniforms</li>
    <li>Resources</li>
    <li>Events</li>
  </ul>
  <p>Here is  a glimpse of a new product record form:</p>
  <figure>
    <figcaption>Product Record</figcaption>
    <img class="Posi-Image-Width-300px-With-Border" src="../../assets/images/new_product_form.png" />
  </figure>
  <p>Do you see anything missing? Do you see a field for Price? No, you don&#39;t, because you don&#39;t set the price for a product until you add it to a Price Book. Price isn&#39;t offered at the product level, because then it would always be offered at the same price to all donors in all opportunities. Instead, by using price books, you can offer multiple prices for the same product. For example, in addition to having a Standard Price Book, you might want to have a Discount Price Book, which offers everything at discounted prices, for special clients.</p>
  <h3 class="POS-H3-BlueTonguedSkink">Opportunity Products</h3>
  <p>Opportunity Products are a standard Salesforce object which creates records by linking products to opportunities.</p>
  <figure>
    <figcaption>Opportunity Product</figcaption>
    <img class="Posi-Image-Width-500px-Border" src="../../assets/images/opportunity_product.png" />
  </figure>
  <p>Think of the Opportunity Product as the marriage of an opportunity to a product selected from your product list. When the donor contributes, the opportunity is linked to a product (with a dollar value) of the donor&#39;s choice, and this becomes the opportunity product. In our example above, you can see how Opportunity and Product are joined in Opportunity Product Name. </p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 6;">Price Books</h1>
  <p>Price Book is a standard Salesforce object used PGE to assign dollar amounts to products which are used in opportunities. You can have several price books in your PGE org to manage price tiers based on end donor, projects, campaigns, specials, etc. Most organisations start with a Standard Price Book, which has full price points associated with products. Products do not have prices associated with them at the product record level. Prices are assigned to a product in a price book.</p>
  <p> </p>
  <p>A price book is just a list of products with prices:</p>
  <figure>
    <figcaption>Standard Price Book</figcaption>
    <img class="Posi-Image-Width-400px-With-Border" src="../../assets/images/price_book.png" />
  </figure>
  <p>You don&#39;t set the price for a product until you add it to a price book. And you can add products only from the price book you associate with the opportunity.</p>
  <figure>
    <figcaption>Choose Price Book</figcaption>
    <img class="Posi-Image-Width-400px-With-Border" src="../../assets/images/price_book_choose.png" />
  </figure>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 7;">Funding Projects</h1>
  <p>Funding Project is a custom Salesforce Object in PGE, which Posimente has introduced to help schools manage fundraising events with requirements different from standard campaigns. Examples of funding projects include facility upgrades, new classrooms, scholarships, major excursions, etc. When a donor contributes to a funding project, they are guided by your organisation to select products which have been added to the funding project. Therefore, when an opportunity is closed/won with that selected product, the amount is automatically rolled up into the totals for the funding project. Products can be specially set up and named for different funding projects, to help manage and track the overall process.</p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 8;">Contacts and accounts</h1>
  <p>Contacts in PGE are still a standard Salesforce object. What differs in PGE from Posi Giving are the relationships available to other objects, and the subsequent page layout. Let&#39;s look at Terrence Whittaker from our example above:</p>
  <figure>
    <figcaption>PGE Contact Example</figcaption>
    <img class="Posi-Image-Width-600px-Border" src="../../assets/images/contact_example.png" />
  </figure>
  <p>The contact Terrence Whittaker is a member of a household account (Whittaker Household) - in the standard way contacts are. On the other contact tabs, you see:</p>
  <ul class="Square">
    <li>Donations: Where Terrence’s opportunities are listed</li>
    <li>Appeals: Where the campaigns Terrence is a member of are listed</li>
    <li>Relationships: Where contact relationships to Terrence are listed (such as family members, employers, fellow students, and more)</li>
    <li>Giving Summary: Where the records of Terrence’s opportunities are displayed, grouped, and totalled with different criteria</li>
    <li>Related: Where files relating to Terrence can be uploaded</li>
  </ul>
  <p>Contact and accounts maintenance is a standard Salesforce process. To learn more, please refer to the Contact And Accounts Maintenance guide available on the Posimente Knowledge Hub.</p>
  <h1 class="POS-Numbering11-Bilby-3" data-list-level="2" style="counter-set: item2 9;">Dashboards</h1>
  <p>Dashboards in PGE are standard Salesforce functionality based on reports. When you first log in to PGE, you are taken to a fundraising performance dashboard.</p>
  <figure>
    <figcaption>Fundraising Performance Dashboard</figcaption>
    <img class="AS-Standard-Border" src="../../assets/images/dashboard_01.png" />
  </figure>
</body>
</html>
