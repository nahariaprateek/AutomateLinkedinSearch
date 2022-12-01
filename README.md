# AutomateLinkedinSearch
Linkedin URL's into Google Sheet, Added through the extensions in googlesheets



Steps to Initiate Linkedin profile search through google sheets using extensions as 

Using Custom Search API & Search EngineID.



Step to Create:-

1. Create an Google Sheet with a template column names as 
  1.1 CompanyName
  1.2 jobTitle
  1.3 linkedinURL	
  1.4 Name

2. CompanyName	|| jobTitle	       || linkedinURL  ||	   Name
   lempire	       CEO		
   lempire	       Head of marketing		


3. Go - to Extensions in google sheet and click on Apps Script.

4. Create the project name & copy the fun_linkedinsearch - code in the repo.

5. follow up on this link in the new tab -> https://developers.google.com/custom-search/v1/overview
    Copy or obtain the API Key -> "Get a Key"
 
6. Paste the API key in the original code of fun_linkedinsearch under "Get a Custom Search API Key" for the variable "var key"
    Eg - > var key = "kfkahf325h2h3htrq3;lhj2;hyl4hl;6hkl2h46lh25l3"

7. follow up on this link in the new tab ->https://programmablesearchengine.google.com/
    7.1 Click on "Add" -> Create a new search engine (LinkedinSearch)- > What to search?(Search the entire web) -> Create.
    7.2 Your new search engine has been created -> Click on "Customize" -> **"Search engine ID"** (Copy This )
    Copy or obtain the Search Engine ID
   
8. Paste the Search Engine ID for the variable "let searchEngineId" in the fun_linkdinsearch function code.

9. Go Back to Google Sheet, created as XXYYZZ.

10. Under the linkedinURL column -> type down the formula as "=getPerson(A2,B2)" and copy the formula in a serialized method to the whole column.

11. You can have all the profiles.














Developed by https://www.linkedin.com/in/lucas-perret/ (Lucas Parret)
