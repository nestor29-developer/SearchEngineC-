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

    <add key="GoogleAPIKey" value="AIzaSyBLaMbfK9qagaUngMR8tz9hzGFVEdaMw_E"/>
    <add key="GoogleSearchEngineID" value="014542846031263441267:ztresdyut3a"/>
    <add key="BINGAccessKey" value="60cdd26bf1e04e22be727e96f0a3e4db"/>