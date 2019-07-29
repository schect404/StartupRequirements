# StartupRequirements

## Roadmap preview of project (by features/use-cases)

### 1. Profile
  - Create profile by login, pwd, Full Name *
  - Create profile via Facebook auth *
  - Create profile via Google auth *
  - Change pwd *
  - Link favourite messenger: Facebook Messenger, Telegram, Skype, Viber, etc
  - Setup preferable delivery methods (DHL, etc)
  - __(Optional)__ Link payment methods
  - __(Optional)__ Display user's contact information below their product publication
  - __(Optional)__ Display real name or pseudo
  - __(VERY Optional)__ 2FA
  
*Each of these actions requires user's confirmation via email (or other)
 
### 2. Product publication
  - Add photos to publication
  - Add Name of product
  - Setup category
  - Setup location (current user's location, selectable on map, or input by adress)
  - Setup price: value, range or specific values as 'discussable' or 'unspecified'. __(VERY Optional)__ 'other', when user proposes exchange
  - __(Optional)__ Automatic category detection and validation (in case user missed the right one)
  - __(VERY Optional)__ Linking of products in 'packs' (bundles)
  
### 3. Published products management
- User should be able to view their publications + quatity of views, saves, etc
- Disable product
- Delete product
- Modify product
- __(Optional)__ Easy linking of products in 'packs' (bundles)
- __(Optional)__ Advertise (promote) publications

### 4. Search products
  - Search in product name, inside content
  - Filter by location
  - Fliter by publication time
  - Filter by category
  - Filtering by fields appropriate for each category
  - Sorting: by publication time, by distance, by price
  - Subscribe by notfications on searches
  - Add to saved items
  - ! Contact the owner (perfectly with possibility to confirm buying from the bot-chat)
  - Buy the product
    - Select the delivery
    - Select payment method (is kinda dependent on delivery)
  - __(Optional)__ Compare products of one category

### 5. Trustability of user ('publisher')
  - Report functionality
  - Ratings
  - __(VERY Optional)__ Certification

### 6. (Optional) Services
  - To-be-done

! Can be bottleneck, cause if user is popular - can receive multiple proposals on each product/service. As a result bot chat can become kloaked by mixing messages from all users on all products.

## Notes on technical requirements (WIP)

### 1. Functionality
  - While surely users' do need some categories and products - there will be plenty of them, so we would rather create the system that doesn't need coding for each new entity and category.
  - Creation of new product should provide some template when selecting the 'category', 'sub-category', etc.
  - Notification system should be attractive for user, so every one will be able to configure it for himself.
  
### 2. Our current plan
  - Investigate existing solutions on the market
  - Discuss and finish feature/use-case description
  - Investigate backend dynamic creation for products
  - Create mockups
  - Implement Web-UI and Android MVP

## Discussions
  - Cross-posting to Facebook marketplace or other (premium? maybe some quantity of products is free, but up of this quantity it becomes payable?)
