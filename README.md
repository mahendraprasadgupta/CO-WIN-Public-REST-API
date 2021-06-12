# CO-WIN-Public-REST-API

Co-WIN Public APIs [Updated on 03 June 2021]
 1.2.1 OAS3
Co-WIN Public APIs allow any third-party application to access certain un-restricted information, that can be shared with its users. This is limited only to read access in Co-WIN. The extent of access will be limited and in case of any misuse impacting the performance of Co-WIN solution will result in blocking any such application and entities as per the policies of MoHFW and taking any other appropriate action in accordance with law. The appointment availability data is cached and may be up to 5 minutes old. Further, these APIs are subject to a rate limit of 100 API calls per 5 minutes per IP. Please consider these points while using the APIs in your application.

Collection Requests
-------------------------

User Authentication APIs

1. Authenticate a beneficiary by Mobile/OTP.
2. Confirm mobile OTP for authentication.

Metadata APIs

3. Get states.
4. Get list of districts.

Appointment Availability APIs

5. Get vaccination sessions by PIN.
6. Get vaccination sessions by district.
7. Get vaccination centers by latitude and longitude.
8. Get vaccination sessions by PIN for 7 days.
9. Get vaccination sessions by district for 7 days.
10. Get vaccination sessions by center for 7 days.

Certificate APIs

11. Download vaccination certificate in PDF format by beneficiary reference id

Resource reference: Co-WIN Public APIs<br>
URL: https://apisetu.gov.in/public/api/cowin/cowin-public-v2
