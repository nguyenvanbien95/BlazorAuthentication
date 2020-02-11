# BlazorAuthentication
Test auth for blazor app

This project have some problems of authentication in Blazor Server side.

I created this project to someone solve this. It is not clear for me.
** Prepare
- Step 1: Clone repository and open it in visual studio (mine is 2019 Version 16.4.4)
- Step 2: Download SDK for .net Core 3.1.

** Run
- Step 3: Run project. Your page is loaded which is login page.
- Step 4: Enter some value for username and password to login.
- Step 5: After login, you will redirect to home page. Open new tab and url for home page. Now, we have two same pages.
- Step 6: Click to Counter page in all tab.
- Step 7: Logout in 2nd tab. And click to button "Click me" in 1st tab. Result is count is continuing increase value but i have logouted.
If We reload page in 1st tab, session will be expired and redirect to login page.
What is my mistake?

Explain for this in https://github.com/dotnet/aspnetcore/issues/18901
