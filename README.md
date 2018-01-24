Project ID: 		Project Name : 																										VERIFIED				
																												CLOSED				
Defect Id.	Module name	Defect Summary	Defect Description		Defect Category	Detected in Browser 	Environment	Defect Severity	Defect Priority	Detected in Release #	Detected in Build #	Reported Date	Reported By	Assigned To	Status	Review type / Test Cycle	Test Case No.	Defect Count	Fixed Date	Verified Date	Verified By	Verified  in Release #	Verified  in Build #	Attachements	Comments			REOPENED	Coding			Internal Dev
DF_HOME_001	Home	The link  is not able to navigate the user to desired web page	Detailed Description:		Coding	Google Chrome	Internal QA	P1	High	1.1	1	22/01/2018	Pranjali & Hilor		ACT		TC_HOME_001										PPR 	FIXED	Design	P0	Low	Internal QA
																											PPR 	ACT	Enhancement	P1	Medium	External Dev
			"
The link  is not able to navigate the user to desired web page
"																								SR	CNR	New Requirement	P2	High	External QA
																											QPR	NOD	Query	P3		
			Steps to reproduce bug:	Test Data																							RT	REP	Documentation	Low		
			1. Open Browser	Google Chrome																							UTC		Master Data	Medium		
			2. Enter URL for the website	www.bankersjob.com/exam																									Test Review	High		
			3. Click on Login link																													
			4. Enter valid Username																													
			5. Enter valid Password																													
			6. Click on Sign In button																													
			7.click on link “List of exams on the portal”																													
			Actual result Observed:																													
																																
			On following the above steps the link should navigate the user to desired web page but the link is not able to do so 		Design	Google Chrome	Internal QA	P3	Low	1.1	1	22/01/2018	Pranjali & Hilor		ACT		TC_HOME_001															
DF_EXAMREG_002	Exam Registration Page	"The link “List of exams on the portal” is displayed at the left side of the web page
instead of right side."	Detailed Description:																													
			The link appears on left side instead of right side of the web page																													
			Actual result Observed:																													
			On following the above steps the link should appear on the left side instead of right side of the page.		Coding	Google Chrome	Internal QA	P1	Medium	1.1	1	22/01/2018	Pranjali & Hilor		ACT		TC_HOME_001															
DF_EXAMREG_003	List of exams	The User Name field is accepting any type of data.	Detailed Description:																													
			The User Name field is accepting any type of data.																													
			Steps to reproduce bug:	Test Data																												
			1. Open Browser	Google Chrome																												
			2. Enter URL for the website	www.bankersjob.com/exam																												
			3. Click on Login link																													
			4. Enter valid Username																													
			5. Enter valid Password																													
			6. Click on Sign In button																													
			Actual result Observed:																													
																																
			On following the above steps the User Name field is accepting special characters and numbers which it should not accept.		Coding	Google Chrome	Internal QA	P1	High	1.1	1	22/01/2018	Pranjali & Hilor		ACT		TC_HOME_001															
DF_EXAMREG_004	List of exams	The application is not generating an error even if Password filed is left empty	Detailed Description:																													
			The application is not generating an error even if Password filed is left empty while logging to the application																													
			Steps to reproduce bug:	Test Data																												
			1. Open Browser	Google Chrome																												
			2. Enter URL for the website	www.bankersjob.com/exam																												
			3. Click on Login link																													
			4. Enter valid Username																													
			5. Enter valid Password																													
			6. Click on Sign In button																													
			Actual result Observed:																													
																																
			On following the above steps the link and leaving the password field empty, the user is able to login instead of generating an error message		Coding	Google Chrome	Internal QA	P1	High	1.1	1	22/01/2018	Pranjali & Hilor		ACT		TC_HOME_001															
DF_EXAMREG_005	List of exams	The user is unable to login even after enter valid user name and password	Detailed Description:																													
			The user is unable to login even after entering valid credential																													
			Steps to reproduce bug:	Test Data																												
			1. Open Browser	Google Chrome																												
			2. Enter URL for the website	www.bankersjob.com/exam																												
			3. Click on Login link																													
			4. Enter valid Username																													
			5. Enter valid Password																													
			6. Click on Sign In button																													
			Actual result Observed:																													
																																
			The application behaves in a wired manner by disallowing a user to login to the website even if the user has entered the valid credential		Coding	Google Chrome	Internal QA	P1	High	1.1	1		Pranjali & Hilor		ACT		TC_HOME_001															
DF_EXAMREG_006	List of exams	The Submit button on the home page user gets an error message	Detailed Description:																													
			The Submit button on the home page user gets an error message “Page Cannot Be Displayed”.																													
			Steps to reproduce bug:	Test Data																												
			1. Open Browser	Google Chrome																												
			2. Enter URL for the website	www.bankersjob.com/exam																												
			3. Click on Login link																													
			4. Enter valid Username																													
			5. Enter valid Password																													
			6. Click on Sign In button																													
			Actual result Observed:																													
																																
			On following the above steps the link after clicking on the Submit button on the home page user gets an error message “Page Cannot Be Displayed”																													
