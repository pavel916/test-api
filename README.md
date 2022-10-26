{
	"info": {
		"_postman_id": "dcb3c45a-f604-4d4b-9b84-005acf6ce8f5",
		"name": "api-1",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "24044683"
	},
	"item": [
		{
			"name": "api-users",
			"request": {
				"auth": {
					"type": "noauth"
				},
				"method": "POST",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"user\": {\r\n    \"email\": \"pavel916@gmail.com\",\r\n    \"password\": \"qwerty123\"\r\n  }\r\n}\r\n",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog.kata.academy/api/users/login",
					"protocol": "https",
					"host": [
						"blog",
						"kata",
						"academy"
					],
					"path": [
						"api",
						"users",
						"login"
					]
				}
			},
			"response": []
		},
		{
			"name": "api-users Copy 2",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "{{tokken}}",
							"type": "string"
						}
					]
				},
				"method": "GET",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text",
						"disabled": true
					}
				],
				"url": {
					"raw": "https://blog.kata.academy/api/user",
					"protocol": "https",
					"host": [
						"blog",
						"kata",
						"academy"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "api-users Copy 3",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "{{tokken}}",
							"type": "string"
						}
					]
				},
				"method": "POST",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text",
						"disabled": true
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"user\": {\r\n    \"username\": \"jhjsh\",\r\n    \"email\": \"ksjhsg@gmail.com\",\r\n    \"password\": \"7765598\"\r\n  }\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog.kata.academy/api/users",
					"protocol": "https",
					"host": [
						"blog",
						"kata",
						"academy"
					],
					"path": [
						"api",
						"users"
					]
				}
			},
			"response": []
		},
		{
			"name": "api-users Copy 4",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "{{tokken}}",
							"type": "string"
						}
					]
				},
				"method": "PUT",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text",
						"disabled": true
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"user\": {\r\n    \"email\": \"agfdsfsg@gmail.com\",\r\n    \"password\": \"zvzvzvz\",\r\n    \"username\": \"lpldjgfhdk\",\r\n    \"bio\": \"ieieueueue\",\r\n    \"image\": \"https://upload.wikimedia.org/wikipedia/commons/0/0e/Felis_silvestris_silvestris.jpg\"\r\n  }\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog.kata.academy/api/user",
					"protocol": "https",
					"host": [
						"blog",
						"kata",
						"academy"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "api-users Copy 5",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "{{tokken}}",
							"type": "string"
						}
					]
				},
				"method": "GET",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text",
						"disabled": true
					}
				],
				"url": {
					"raw": "https://blog.kata.academy/api/user",
					"protocol": "https",
					"host": [
						"blog",
						"kata",
						"academy"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		}
	]
}