# Linq Profile Flow QA Analyst Take-Home Assessment

## Overview

In this QA Analyst Take-Home Assessment, I tested key user flows on the Linq profile page. The focus was on verifying the phone number signup process, reauthentication after accessing the profile, and ensuring the profile layout adapts correctly on mobile and desktop devices. The assessment is designed to evaluate my attention to detail, communication, and technical aptitude in documenting manual test cases and inspecting API requests using Postman.

## Test Scenarios Covered

### 1.   Signing up with Phone Number  
   - Verified that a user can successfully sign up using their phone number.
   - Validated that the login/signup process completes without errors.

### 2.   Reauthentication After Profile Access  
   - Ensured that after entering the verification code, the user is required to reauthenticate if they navigate back to the page or leave the session.

### 3.   Profile Page Load  
   - Checked that the Linq profile page loads correctly without errors, ensuring that all profile details (name, image, bio, and contact buttons) are visible.
   
### 4.   Profile Layout on Different Devices  
   - Verified that the profile page layout adapts properly across different screen sizes (desktop, mobile) without any UI distortion or overlapping text.

## API Testing with Postman

I used Postman to inspect relevant API endpoints, simulate interactions, and investigate network activity. I encountered a 401 Unauthorized error when trying to access the API due to missing authentication credentials (Bearer token). The findings and concerns are documented in the Postman notes file.

## Deliverables

-   test-cases.md  : Detailed manual test cases for the Linq profile flow.
-   bugs.md  : Bug reports for any issues encountered during testing.
-   postman-notes.md  : Notes from inspecting the API, including request/response details and encountered issues.

## Conclusion

This assessment demonstrates my ability to perform manual testing, document results, and inspect API behavior. The submission is organized in a GitHub repository for easy review and includes clear and concise documentation for all deliverables.
