**Project**  

Application for Android food delivery. The cycle in which we test the subscription function. The subscription provides free delivery of orders within a pre-configured delivery distance. The first 14 days of the subscription is a trial period. "Normal" paid subscription starts after the trial period.  
  
**Test Cycle:**  

- Shopping with the new functionality activated. Testing all new features with it.
- Testers, had to check an essential new functionality works as expected in real-world conditions
- Sites with the 'new functionality' are visible and accessible to customers in the cities included in the pilot phase.
- Customers can log in to the 'new functionality' service using actual payment methods.
    
**Test Cycle Period:**  

1st stage, testing trial period, lasts 14 days. Whether it is visible or becomes activated when you select it.  
2nd stage 14 days later, when the trial period ends - to see if subscription money is transferred.

**Requirements**:   

Specific Real Localization
Platforms: Web, Android v.6 or greater, iOS v.12 or 

**Test Objective:**  

- Users had to test the app to find venues with special discount price regarding the activated subscription plan  
- User needs to have at least 3 venues within ~3km of the user location  
- If the user didn't have 3 venues close by, the special feature wasn't shown at all  
- Venues providing support for special discount are displayed with a “special” icon

--​ Discovery view subscription flow: Check Discovery view for subscription ads
-  Sign into the trial period
-  Create an order with special feature delivery
-  Make sure delivery costs are as expected (without fee)

-- Checkout subscription flow (exploratory)  
- Start an order with a "special price feature" venue and ensure this is advertised during the checkout process (how & where?)
