# URL:
https://petstore.swagger.io/v2/user

# Collection:
petstore.swagger.io user

# POST
Create user
```json
		{
			"name": "Create user",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"id\": 0,\r\n  \"username\": \"privettest\",\r\n  \"firstName\": \"test\",\r\n  \"lastName\": \"test\",\r\n  \"email\": \"sveta@gmail.com\",\r\n  \"password\": \"testtest\",\r\n  \"phone\": \"23456789\",\r\n  \"userStatus\": 0\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user"
					]
				}
			},
			"response": []
		}
```
# GET
Login
```json
		{
			"name": "Login",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/login?username =privettest&password =testtest",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"login"
					],
					"query": [
						{
							"key": "username ",
							"value": "privettest"
						},
						{
							"key": "password ",
							"value": "testtest"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Logout
```json
		{
			"name": "Logout",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/logout",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"logout"
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete user
```json
		{
			"name": "Delete user",
			"request": {
				"method": "DELETE",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/privettest?username =privettest",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"privettest"
					],
					"query": [
						{
							"key": "username ",
							"value": "privettest"
						}
					]
				}
			},
			"response": []
		}
```
# PUT
Update user
```json
		{
			"name": "Update user",
			"request": {
				"method": "PUT",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\n  \"id\": 0,\n  \"username\": \"privettest\",\n  \"firstName\": \"test\",\n  \"lastName\": \"test\",\n  \"email\": \"test@gmail.com\",\n  \"password\": \"55555\",\n  \"phone\": \"55555\",\n  \"userStatus\": 0\n}"
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/privettest?username=privettest",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"privettest"
					],
					"query": [
						{
							"key": "username",
							"value": "privettest"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Get user by name
```json
		{
			"name": "Get user by name",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/privettest?username =privettest",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"privettest"
					],
					"query": [
						{
							"key": "username ",
							"value": "privettest"
						}
					]
				}
			},
			"response": []
		}
```
# POST
createWithList
```json
		{
			"name": "createWithList",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "[\r\n  {\r\n    \"id\": 9223372036854757513,\r\n    \"username\": \"privettest\",\r\n    \"firstName\": \"test\",\r\n    \"lastName\": \"test\",\r\n    \"email\": \"sveta@gmail.com\",\r\n    \"password\": \"testtest\",\r\n    \"phone\": \"23456789\",\r\n    \"userStatus\": 0\r\n  }\r\n]",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/createWithList",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"createWithList"
					]
				}
			},
			"response": []
		}
```
# POST
createWithArray
```json
	
		{
			"name": "createWithArray",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "[\r\n  {\r\n    \"id\": 9223372036854757513,\r\n    \"username\": \"privettest\",\r\n    \"firstName\": \"test\",\r\n    \"lastName\": \"test\",\r\n    \"email\": \"sveta@gmail.com\",\r\n    \"password\": \"testtest\",\r\n    \"phone\": \"23456789\",\r\n    \"userStatus\": 0\r\n  }\r\n]",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/user/createWithArray",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"user",
						"createWithArray"
					]
				}
			},
			"response": []
		}
```
