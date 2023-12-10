# URL:
https://reqres.in/api

# GET
Get list
```json
		{
			"name": "Get list",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/users?page=2",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					],
					"query": [
						{
							"key": "page",
							"value": "2"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Single user
```json
		{
			"name": "Single user",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/users/5",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"5"
					]
				}
			},
			"response": []
		}
```
# GET
Single user not found
```json
		{
			"name": "Single user not found",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/users/23",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"23"
					]
				}
			},
			"response": []
		}
```
# GET
List resourse
```json
		{
			"name": "List resourse",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/unknown",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"unknown"
					]
				}
			},
			"response": []
		}
```
# GET
Single resource
```json
		{
			"name": "Single resource",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/unknown/2",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"unknown",
						"2"
					]
				}
			},
			"response": []
		}
```
# GET
Single resource not found
```json
		{
			"name": "Single resource not found",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/unknown/23",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"unknown",
						"23"
					]
				}
			},
			"response": []
		}
```
# POST
Create
```json
		{
			"name": "Create",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\": \"sveta\",\r\n    \"job\": \"qa\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					]
				}
			},
			"response": []
		}
```
# PUT
Update
```json
		{
			"name": "Update",
			"request": {
				"method": "PUT",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\": \"svetlana\",\r\n    \"job\": \"qa\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users/2",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"2"
					]
				}
			},
			"response": []
		}
```
# PATCH
Update
```json
		{
			"name": "Update",
			"request": {
				"method": "PATCH",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\": \"svetla\",\r\n    \"job\": \"qa\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users/2",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"2"
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete
```json
		{
			"name": "Delete",
			"request": {
				"method": "DELETE",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/users/2",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"2"
					]
				}
			},
			"response": []
		}
```
# POST
Register - successful
```json
		{
			"name": "Register - successful",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"email\": \"eve.holt@reqres.in\",\r\n    \"password\": \"pistol\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/register",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"register"
					]
				}
			},
			"response": []
		}
```
# POST
Register - unsuccessful
```json
		{
			"name": "Register - unsuccessful",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"email\": \"sydney@fife\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/register",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"register"
					]
				}
			},
			"response": []
		}
```
# POST
Login - successful
```json
		{
			"name": "Login - successful",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"email\": \"eve.holt@reqres.in\",\r\n    \"password\": \"cityslicka\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/login",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"login"
					]
				}
			},
			"response": []
		}
```
# POST
Login - unsuccessful
```json
		{
			"name": "Login - unsuccessful",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"email\": \"peter@klaven\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/login",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"login"
					]
				}
			},
			"response": []
		}
```
# GET
Delayed response
```json
		{
			"name": "Delayed response",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://reqres.in/api/users?delay=3",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					],
					"query": [
						{
							"key": "delay",
							"value": "3"
						}
					]
				}
			},
			"response": []
		}
```
