**Project**

Web site, one of the leading e-commerce
  
**Test Cycle:**

The functional cycle of the website
The whole website is in scope including the emails
The checkout process may be completed (not for mobile phone products) 
    
**Test Cycle Period:**

2 days

**Requirements:** 

Desktops:  
Windows 8 and higher  
Browsers: Chrome (from version 89), Firefox (from version 86), Edge (from version 89)  

Mac OS 10.14.x and higher  
Browsers: Chrome (from version 89), Firefox (from version 86), Safari (from version 14)  

Tablets & Smartphones:
iOS 12 and higher - Chrome (latest version), Safari
Android 5 and higher - Chrome (latest version), Samsung Stock Browser (from version 13.2)
Android hero devices: Samsung Galaxy A51, Samsung Galaxy S10, Huawei P30, Xiaomi Redmi Note 8 Pro

**Test Objective:**  

Search on mobiles:
The slider on the results page is now displayed at the bottom of the screen 
Cross Channel functionality:
- No store address is shown on the grey button on the product detail page, if the user is not logged in or the item is currently not available in their favorite store or loading the page takes more than 5 seconds
- Logic for store on the button should look first for a saved favorite store  
-- If none exists, check the purchase history for delivery to a store  
-- otherwise find a store close to the billing address

**Logical for: Click & Reserve vs Click & Collect:**
- Click & Collect (= item will get sent to the store for payment and pickup, normal checkout process with a store as delivery address, free delivery, requires login)
- Click & Reserve (= item is available in the specific store and will be set aside for the user, no checkout flow)
​- You can reserve an item if it is in stock in the selected store
- You can order an item via Click & Collect if it is available online and not in stock in the selected store


