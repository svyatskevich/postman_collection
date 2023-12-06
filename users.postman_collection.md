# URL
http://users.bugred.ru
# Collection
```json
{
	"info": {
		"_postman_id": "acb9e64e-d33f-4e09-b10c-fe5694377c58",
		"name": "Users",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "24863260"
	},
	"item": [
		{
			"name": "doRegister",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Status code is 200\", function () {\r",
							"    pm.response.to.have.status(200);\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "\r\n{\r\n    \"email\": \"mil@mail.ru\",\r\n    \"name\": \" SY\",\r\n    \"password\": \"1\"\r\n}"
				},
				"url": {
					"raw": "http://users.bugred.ru/tasks/rest/doregister",
					"protocol": "http",
					"host": [
						"users",
						"bugred",
						"ru"
					],
					"path": [
						"tasks",
						"rest",
						"doregister"
					]
				}
			},
			"response": []
		},
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
		},
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
		},
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
		},
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
		},
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
	]
}
```
