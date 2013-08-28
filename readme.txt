1. This project is developed with visual studio 2012 based on .Net framework 4.0 and MVC 4.0.

2. The test framework microsoft unit test.

3. IoC container is latest version AutoFac.

4. Final UAT is method Content_Returned_to_Browser_Should_Not_Be_Null, 
	and unit test is method Tweets_Json_Result_Should_Not_Be_Null 
	in PBP.Jason.Yan.Assignment\PBP.Tweets.Mvc.Tests\Controllers\TweetsControllerTest.cs. 

   for UAT running, the web application should be start in advance.

5. After running web application, the url in browser should be changed to http://localhost:2039/tweets/latestlist/paybyphone mannually.
	the last section [paybyphone] is a query parameter, it could be any twitter user account name.

6. For test reason, the timespan is set to 3 weeks or 21 days.

7. Central control to error and exception is not implemented.
