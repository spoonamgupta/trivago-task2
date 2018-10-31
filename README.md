# trivago-task2

This project contains the automated test-scripts generated through Selenium IDE for the following tasks -

  1. Search for any location on Room5 by using the search bar 
  2. Fill in the contact form and send it (accessible through the footer) 
  3. Subscribe to the Newsletter
  4. Navigate to a destination through the menu on the top left
  5. Create 2 different automated test cases for the actions you think are the most important to automate -
    (a). Select a country form footer locale drop down
    (b). Navigate to a destination through the menu on the top left and click 'Load More'
    
 Reason for choosing 5(a) and 5(b) -
 
 5(a). Footer locate drop down  - I chose to automate this scenario because it should not impact the users of any country.
       
 5(b). Destination_page load more test - It is important to test this scenario because Users should always be able to navigate        complete page using load more button.  

Note - 

The test scripts attached with this project have following limitations -

  1. Search for any location on Room5 by using the search bar -  
     This test can only check the functionality of the search bar, as the content of the page is dynamic and asserting over        any dynamic content may cause the test to fail even if the search bar is working fine.
  
  2. Fill in the contact form and send it  -
     This test requires mannual testing from QA team, as the feedback may have not recieved in the target location because of      some glitch in the code.
     
  3. Subscribe to the Newsletter - 
     This test requires mannual testing from the users side, as the user may not get updates even after subscribing to the          Newsletter.
  
  4. Navigate to a destination through the menu on the top left - 
     This test can only check the functionality of the navigation bar, as the content of the page is dynamic and asserting          over any dynamic content may cause the test to fail even if the navigation bar is working fine.     
