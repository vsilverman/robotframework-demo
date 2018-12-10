# Automated testing using Robot Framework
This repo shows sample of automating the testing of localhost site using robotframework.

## Steps to Execute This Sample

-	Clone this sample by using e.g. the following command

			git clone <git-address-of-this-repo>

-	Verify that python installation package (pip) is
    available on your machine.  If not - install it.

-   Verify that robotframework and Selenium2Libranry for
    robotframework are installed on your machne.
    You can do that by running the following command:
    
            pip list | grep robotframework
        
-   If any of those are not available you can install
    them through the pip comommand, e.g.:
    
            pip install robotframework-selenium2library
    
-	Start the local python demo server on port 7272:

	        python demoapp/server.py 7272
	
-   Execute all login tests, automated through robotfamework 
    keywords:

            robot login-tests
            
-   Observer how robotframework generated new files,
    containing test results.  Explore those results
    by pointing your browser to generated report.html file.