===============
GO / Golang Rest API Demo
===============

This is a GO Rest API demo to understand the basics of Go / Golang

**Use the API**
____

Get index
-

* URL

**/**

* Method

"GET"

* SUCCESS RESPONSE

Code: 200

This will return a welcome message

----

Check status
-

* URL

**/ping**

* Method

"GET"

* SUCCESS RESPONSE

Code: 200

This will return a "pong" message if webserver is running ok.

----

Get Items
-

* URL

**/items**

* Method

"GET"

* SUCCESS RESPONSE

Code: 200

This will return a list of all items in the collection.

----

Create a new Item
-

* URL

**/items**

* Method

"POST"

* BODY

      {"name":"New Item"}

* SUCCESS RESPONSE

Code: 201

----

Get Item by ID
-

* URL

**/items/{itemId}**

* Method

"GET"

* SUCCESS RESPONSE

Code: 200

This will return the information for a particula item.

      {"id":2,"name":"Mercadolibre - Item 2","completed":false,"due":"0001-01-01T00:00:00Z"}

----

Delete Item by ID
-

* URL

**/items/{itemId}**

* Method

"DELETE"

* SUCCESS RESPONSE

Code: 200

This will delete a a particular item by ID.

----

* Questions?

Ask fabianbertetto@gmail.com.com

Pull requests are welcome
