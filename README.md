Helps to find the covid vaccination availability on official government website. Specify the dist code and date to find the vaccine available
Run the file in cmd and check the district code ypu want to get vaccinated and the specify the date you want to be vaccinated
Run the code, the program would find the available places to get vaccinated and returns the "No vaccine available" message if there are no slots available in the dist selected
Working
The packages used are-request,time
The time package is not important if the program is recursive
The url of the API is available in the official governmet site- "https://apisetu.gov.in/public/marketplace/api/cowin"
The Api used in this project is /v2/admin/location/districts/{state_id} under METADATA APIs
The url is used to optain the url for request
After the request is made the response which json format is converted into readable data using for loop.
