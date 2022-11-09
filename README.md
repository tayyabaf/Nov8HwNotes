# Nov8HwNotes
API
>Application programming interface
>
> A tool which makes a website's data disgestable for the computer
> 
> The "hidden" portion of a website that is meant for computer
consumption


> Server is a powerful computer that runs an API
> >Can store data, send emails, and more

>When 2 systems (websites, desktops, phones) link up through an API, they are "integraated"
>
> Two sides
> >Server - provides API
> >
> >Client - separate program that knows what data is available thru API and can manipulate it, usually thru request of user

>Common HTTP methods
> >get, post, put, delete
> 
> request - consists of a URL (http://…), a method (GET, POST, PUT,
DELETE), a list of headers (User-Agent…), and a body (data). 
> 
> Response - consists of a status code (200, 404…), a list of headers,
and a body. 

> JSON - javascript object notation
> 
> object - a thing or noun
> 
> key - attribute about an object
> 
> value - value of an attribute
> 
> associative array - nested object
> 
> XML - extensible markup language

>authentication - process of client proving its identity to server
> 
> credentials - username, password etc
> 
> basic auth - scheme that uses encoded username and password for credentials
> 
> API key auth - scheme that uses unique key for credentials
> 
> authorization header - HTTP header used to hold credentials

> OAuth - an authentication scheme that automates the key
exchange between client and server
>
>Access Token - a secret that the client obtains upon successfully
completing the OAuth process
>
>Scope -  permissions that determine what access the client has to
user's data
> 
> REST - api archeitecture centered around manipulating resources
> 
> resource - busines noun like customer or order
> 
> endpoint - URL that makes up part of an API
> 
>pagination - process of splitting up results into managable chunks