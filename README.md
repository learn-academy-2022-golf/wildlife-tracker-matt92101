Create an animal
Post http://127.0.0.1:3000/animals/

{
    "common_name": "Cat",
    "scientific_binomial": "Felis Domestica"
}
{"id":2,"common_name":"Cat","scientific_binomial":"Felis Domestica","created_at":"2022-12-13T21:27:29.799Z","updated_at":"2022-12-13T21:27:29.799Z"}

Update an animal
Patch - http://127.0.0.1:3000/animals/1
Updated - Capitalized dog--> Dog 
          Capitalized canis lupus-->Canis Lupus

"id":1,"common_name":"Dog","scientific_binomial":"Canis Lupus","created_at":"2022-12-13T19:40:07.898Z","updated_at":"2022-12-13T21:21:14.518Z"}

Remove and animal
Delete - http://127.0.0.1:3000/animals/1
Removed id:1
Delete

"id":1,"common_name":"Dog","scientific_binomial":"Canis Lupus","created_at":"2022-12-13T19:40:07.898Z","updated_at":"2022-12-13T21:21:14.518Z"}