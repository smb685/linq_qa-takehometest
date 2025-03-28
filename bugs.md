# BUG_001

## Description Ensure that the User is able to signup with their phone number. 
-   Steps:    
  1. Navigate to [Linq Profile Page](https://linqapp.com/welcome).  
  2. "Click" inside of phone number feild.  
-   Expected Result:    
  - The should  be able to complete login/signup without errors.  

-   Actual Results:   
    - User was able to continue through the login/signup process.

- # Status
    - # PASSED


# BUG_002 - Verify if User has to reauthenticate after gaing access to profile.   
-   Description:   Ensure that the User has to get another Verification Code to gain access to the profile.
-   Steps:    
  1. Navigate to [Linq Profile Page](https://linqapp.com/welcome).  
  2. "Click" inside of phone number feild.  
  3. "Enter" the code that is given once the it is sent via text
  4. Navigave through the dashboard.
  5. "Click" the "Back Button" inside of browser used until you are back at the Verification Code screen. 
  6. Then "click" Forward in history mode of browser without entering a code.
-   Expected Result:    
  - The should have to receive/use another code to reauthenticate/gain access to the dashboard.

-   Actual Results:   
    - The User was able to gain access without having to reauthenticate.

- # Status 
    # FAILED


# BUG_003 - Verify Profile Page Loads Successfully.   
-   Description:   Ensure that the Linq profile page loads correctly without errors.  
-   Steps:    
  1. Navigate to [Linq Profile Page](https://linqapp.com/welcome).  
  2. Observe the profile information displayed.  
  3. "Click" inside of phone number feild.  
  4. "Enter" the code that is given once the it is sent via text
-   Expected Result:    
  - The page should load without errors.  
  - Profile details (name, image, bio, contact buttons) should be visible.  
  - No broken images or missing elements.  

 -   Actual Results:  
 - The User was able to Load the page after verification.

 - # Status 
    # PASSED


# BUG_004 - Verify Profile Page Layout on Mobile and Desktop  
 -   Description:   Ensure the profile page adapts correctly on different screen sizes.  
-   Steps:    
  1. Open the profile page on a desktop browser.  
  2. Resize the window to simulate different screen sizes.  
  3. Open the page on a mobile device (iOS/Android).  
-   Expected Result:    
  - The profile layout should remain visually consistent.  
  - No overlapping text or UI distortion. 

   -   Actual Results:  
  - The profile layout remained visually consistent.  
  - There was no overlapping text or UI distortion. 

 - # Status 
    # PASSED

