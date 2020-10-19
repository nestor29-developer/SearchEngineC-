Searchfight Challenge
To determine the popularity of programming languages on the internet we want to you to write an application that queries search engines and compares how many results they return, for example:

    C:\> searchfight.exe .net java

    .net: Google: 4450000000 BING Search: 12354420
    java: Google: 966000000 BING Search: 94381485
    Google winner: .net
    BING Search winner: java
    Total winner: .net

Rules
The application should be able to receive a variable amount of words.
The application should support quotation marks to allow searching for terms with spaces (e.g. searchfight.exe “java script”).
The application should support at least two search engines.



API KEY OPTIONAL WHETHER IS NECESSARY TO COMPILE CORRECTLY:
Out of the box Searchfight implements the Google and Bing Search Engines, so you will need the following:

Google API Key
Google Custom Context Id
Bing Search Engine Key
Once you have them, in order for the application to work you have update the "App.config" file. You will need the following:

    <add key="GoogleAPIKey" value="UPDATE_YOUR_GOOGLE_API_KEY_HERE"/>
    <add key="GoogleSearchEngineID" value="UPDATE_YOUR_GOOGLE_SEARCH_ENGINE_ID_HERE"/>
    <add key="BINGAccessKey" value="UPDATE_YOUR_BING_API_KEY_HERE"/>