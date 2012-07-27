User details
=============

*Access Levels*    
__Group:__ general     
__Resource:__ user_details

List account details
-------------------

```php
GET 	https://api.create.net/user_details
```

### Response

```console
Status: 200 OK
```

```json
{ "user_details" :[ 
	{
		"ID" : "18766",
		"username" : "rachel",
		"firstname" : "Andrew",
		"lastname" : "Doyle",
		"email" : "enquiries@hmdoyle.co.uk",
		"telephone" : "01226 295891"
		"vat_number" : NULL,
		"signup_date" "2002-10-14"
	}
]}

Update account_details
------------------

```php
PUT 	https://api.create.net/user_details
```

### Input

* *firstname* [string]
* *lastname* [string]
* *email* [string]
* *telephone* [string]
* *vat_number* [string]

### Response

```console
Status: 200 OK
```