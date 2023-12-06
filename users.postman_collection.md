# URL
http://users.bugred.ru

# POST
addavatar
```json
		{
			"name": "addavatar",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "email",
							"value": "mil@mail.ru",
							"type": "text"
						},
						{
							"key": "avatar",
							"type": "file",
							"src": "/C:/Users/37525/OneDrive/Рабочий стол/bb3859f36f5dc1ddca239ad8370cc23a.jpg"
						}
					]
				},
				"url": {
					"raw": "http://users.bugred.ru/tasks/rest/addavatar",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						"tasks",
						"rest",
						"addavatar"
					]
				}
			},
			"response": []
		}
```
# GET
Page
```json
		{
			"name": "Page",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "email",
							"value": "svtkrn@test.test",
							"type": "text"
						},
						{
							"key": "name",
							"value": "SY",
							"type": "text"
						},
						{
							"key": "password",
							"value": "12345",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://users.bugred.ru/?page_mg=2&fwlb pfrf",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						""
					],
					"query": [
						{
							"key": "page_mg",
							"value": "2"
						},
						{
							"key": "fwlb pfrf",
							"value": null
						}
					]
				}
			},
			"response": []
		}
```
# DELETE
deleteavatar
```json
		{
			"name": "deleteavatar",
			"request": {
				"method": "DELETE",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "email",
							"value": "svtkrn@test.test",
							"type": "text"
						},
						{
							"key": "name",
							"value": "SY",
							"type": "text"
						},
						{
							"key": "password",
							"value": "12345",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://users.bugred.ru/tasks/rest/deleteavatar?email=ml@mail.ru&",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						"tasks",
						"rest",
						"deleteavatar"
					],
					"query": [
						{
							"key": "email",
							"value": "ml@mail.ru"
						},
						{
							"key": "",
							"value": null
						}
					]
				}
			},
			"response": []
		}
```
# POST
foundCount
```json
		{
			"name": "foundCount",
			"event": [
				{
					"listen": "prerequest",
					"script": {
						"exec": [
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "query",
						"value": "",
						"type": "text"
					},
					{
						"key": "",
						"value": "",
						"type": "text"
					}
				],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "query",
							"value": "svtkrn@test.test",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://users.bugred.ru/tasks/rest/magicsearch?query=SY",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						"tasks",
						"rest",
						"magicsearch"
					],
					"query": [
						{
							"key": "query",
							"value": "SY"
						}
					]
				}
			},
			"response": []
		}
```
# POST
createCompany
```json
		{
			"name": "createCompany",
			"event": [
				{
					"listen": "prerequest",
					"script": {
						"exec": [
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "query",
						"value": "",
						"type": "text"
					},
					{
						"key": "",
						"value": "",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"company_name\": \"компаниятест\",\r\n  \"company_type\": \"ООО\",\r\n  \"company_users\": [\"newtestovich1@mail.ru\",\"dumbledore@mail.ru\"],\r\n  \"email_owner\": \"aa+1@mail.com\"\r\n} "
				},
				"url": {
					"raw": "http://users.bugred.ru/tasks/rest/createcompany",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						"tasks",
						"rest",
						"createcompany"
					]
				}
			},
			"response": []
		}
	

```
