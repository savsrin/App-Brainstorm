Original App Design Project - README Template
===

# Sustainable Fashion Market 

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This app provides a streamlined, fashion-focused matching process and platform for people to buy and sell sustainable (used or handmade) clothing items. Sellers will be able to upload pictures of clothing items they wish to sell along with item metadata (e.g., item type, condition, sizing measurements, picture of seller wearing the clothing, price etc.) that will be used for the matching process. Buyers will then be able to search for a specific item and they will get matched with available items in their area based on criteria such as pricing, sizing, and item condition. If interested, a buyer can request to buy an item, and a seller can approve the request. Once successfully matched, buyers and sellers will then be able to chat to arrange item exchange and payment details. 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Sustainable Fashion & Commerce
- **Mobile:** This app will make use of the mobile camera so that sellers can photograph and upload items they wish to sell; additionally, it will make use of device location to match buyers and sellers by area. 
- **Story:** Provides a convenient and streamlined platform for people to get involved in sustainable fashion/thrifting; once a variety of users are onboarded on the app, this will make opting out of the fast fashion industry a realistic option for more people since current environmentally friendly brands are prohibitively expensive. 
- **Market:** Anyone who's looking to buy/sell clothes and wants to be more environmentally friendly with their fashion choices. Ability to be matched by location, pricing, sizing, and garment type makes it a convenient and appealing option for users. 
- **Habit:** Buysrs can browse as needed for new items, and sellers can check their dashboard of items daily to see if anyone is interested in their items. Sellers will create on the app and buyers will consume on the app. 
- **Scope:** Will focus on the matching process and seller/buyer account types first, and then as time permits, will expand to include more features. The matching process and desigining user flow for both buyers/sellers is definitely a technically challenging problem. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Multiple views
* Interacts with database 
* Log in/log out 
* SDKS/APIs: Facebook/Instagram/Google OAuth/Login (for user login), Google Maps (For location matching), Messenger API (for chatting)
* Sign up for new user profile (both seller and buyer)
* One gesture
* One animation 
* External library for visual polish 
* Technical problem: Matching users together 

**Optional Nice-to-have Stories**

* In house payment 
* Combining buyer and seller accounts into one 
* Browse feature for users + not logging in for browsing 
* Review feature
* Verified seller/buyer process 
* Edit item details after uploading
* Seller can suggest another item/seller if they deny a buyer request

### 2. Screen Archetypes

* Login Screen
    * Buyer can login 
    * Seller can login
* Registration Screen
    * Buyer can create a new account 
    * Seller can create a new account 
* Seller Dashboard
    * Seller can view dashboard of items they've uploaded 
    * Seller notified when a buyer requests an item and can screen the buyer info / accept request 
* Creation
    * Seller can post new item to dashboard with metadata (camera integration)
* Chat 
    * Seller and Buyer can chat to decide details for transaction (Messenger API)
* Search 
    * Buyer can search for item they are looking for, and view seller profiles
    * Buyer can request a seller who they are interested in 


### 3. Navigation

**Tab Navigation** (Tab to Screen)

Seller 
* Dashboard/Home Screen w current items (previous transactions)
* Approve/Deny Buyer Requests 
* Add New Item 
* Chat

Buyer
* Previous Transactions 
* Search 
* Request Status 
* Chat
* 

**Flow Navigation** (Screen to Screen)

Seller / Buyer
* Login
   * -> Home

* Registration 
   * -> Home 
* Buyer: Search Screen 
   * -> Seller Match Feed
 * Seller Feed Screen 
     * -> Item/Seller Details + Send Request Screen
* Seller: Creation Screen 
    * -> Home 
* Seller: Dashboard / Notifications for each item 
    * -> Buyer Details Approve/Deny Buyer Screen 
* Matched Screen 
    * -> Chat Screen 


   


## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
