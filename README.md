Getting latitude and longitude for a list of places

This code uses Google geocoding API to get the lattitude
and the longitude of a list of places.

I took the code presented at this site?

http://www.aspsnippets.com/Articles/Google-Maps-API-V3-Get-Latitude-and-Longitude-of-a-location-from-Address-using-JavaScript.aspx

and modified it so that a list of places can be provided and 
for each click of a buttom the top item in the list
is queried and the result is presented.
So if you have a list of 3 sites you have to click the buttom
3 times.
The result is also presented in a text area on the right side 
of the screen, instead of in an alert box (which was the way
the original code did).
This allows you to mark the results and copy-paste somewhere else.
My particular interest was to use the results as a CSV file
which later I read from R and plot the cities in a map.

I hope this code is useful to you.
