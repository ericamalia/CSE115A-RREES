For system unit testing, all team members contributed to testing two major components: 

# Backend API testing:
* This is to see whether or not the server is behaving as expected.  Sometimes the power goes out and the certain server applications don't work. 
* [System and Unit Test Report](https://docs.google.com/document/d/1JFMbYzD89msBOQERkjt_H4sloGaCTcX-JBhMCaSpqAY/edit?pli=1 "Backend API 
endpoints")
* The file **Intrusive Endpoint Testing.postman_collection.json** is for testing most equivalence classes and load testing in Postman.  

# Frontend Website testing:
* This is close to BlackBox testing, where we test every path in the website to make sure it behaves expectedly.  
* [System and Unit Test Report](https://docs.google.com/document/d/1qUQHPPe7UBGFNDUO_wVAENJsxExyQ0l9NPY9Q5Xg4zs/edit "Frontend website")

# Penetrative testing:
* This testing is to make sure SQL injections and XSS and XSRF requests can't be exploited.
* Using the program OWASP ZAP, it detected no High Risk vulnerabilities.  There are only Medium and Low, which involves the leakage of private IPs, and X-Frame-Options header is not included in the HTTP response to protect against 'ClickJacking' attacks.
* The photo above **Pen_testing.jpg** shows the results of the scan.   
