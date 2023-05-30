# Postman
## Homework 1
### Запросы

Для начала нужно создать запросы Postman, для этого нужно указать протокол, id, port.
```
Protocol: http
Id: 162.55.220.72
Port: 5005
```
---
### EP_1
```
Method: GET
EndPoint: /get
request url params:
	name: str
	age: int
```
_Вывод_
```
[
    "Daniil",
    "19"
]
```
---
### EP_2
```
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int
```
_Вывод_
```
{
    "age": "19",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "u_salary_1_5_year": 56000
    },
    "name": "Daniil",
    "salary": 14000
}
```
---
### EP_3
```
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int
```
_Вывод_
```
{
    "age": 19,
    "daily_food": 0.9,
    "daily_sleep": 187.5,
    "name": "Daniil"
}
```
---
### EP_4
```
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int
```
_Вывод_
```
{
    "person": {
        "u_age": 19,
        "u_name": [
            "Daniil",
            14000,
            19
        ],
        "u_salary_5_years": 58800.0
    },
    "qa_salary_after_1.5_year": 46200.0,
    "qa_salary_after_12_months": 37800.0,
    "qa_salary_after_3.5_years": 53200.0,
    "qa_salary_after_6_months": 28000,
    "start_qa_salary": 14000
}
```
---
### EP_5
```
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int
```
_Вывод_
```
{
    "age": "19",
    "family": {
        "children": [
            [
                "Alex",
                24
            ],
            [
                "Kate",
                12
            ]
        ],
        "pets": {
            "cat": {
                "age": 3,
                "name": "Sunny"
            },
            "dog": {
                "age": 4,
                "name": "Luky"
            }
        },
        "u_salary_1_5_year": 56000
    },
    "name": "Daniil",
    "salary": 14000
}
```
---
### EP_6
```
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int
```
_Вывод_
```
{
    "age": 19,
    "name": "Daniil",
    "salary": [
        14000,
        "28000",
        "42000"
    ]
}
```
---
### EP_7
```
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int
```
_Вывод_
```
{
    "person": {
        "u_age": 19,
        "u_name": [
            "Daniil",
            14000,
            19
        ],
        "u_salary_5_years": 58800.0
    },
    "qa_salary_after_1.5_year": 46200.0,
    "qa_salary_after_12_months": 37800.0,
    "qa_salary_after_3.5_years": 53200.0,
    "qa_salary_after_6_months": 28000,
    "start_qa_salary": 14000
}
```
