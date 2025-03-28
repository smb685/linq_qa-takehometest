
# postman_notes": "I used Postman to simulate saving a contact or interacting with the Linq profile page, specifically interacting with the endpoint: https://api.linqapp.com/api/v2/user_contacts/3165547/user_contact_activities.\n\nI attempted to simulate saving contact info using the following payload: \n{\"activity_type\": \"contact_saved\", \"activity_details\": {\"contact_name\": \"John Doe\", \"phone\": \"+1234567890\", \"email\": \"john.doe@example.com\"}}.\n\n

# However, due to the missing Authorization token, the request failed, and no data was saved or processed.\n\nThe request returned a 401 Unauthorized error, with the response body: \n{\"error\": {\"type\": \"unauthorized\", \"messages\": [\"You can't see that\"]}, \"status\": \"unauthorized\"}.\n\n 

# This response indicates that the API is preventing access due to a missing or invalid Authorization token.

# The primary concern here is that without the Authorization token, I cannot interact with the API and test the desired functionality, such as saving contact info and interacting with user contact activities.

# My questions are: How can I obtain a Bearer token for the API to proceed with testing? Is there a specific authentication process (like OAuth) that I can follow to get the token?"

