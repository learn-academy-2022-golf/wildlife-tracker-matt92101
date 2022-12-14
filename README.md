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

STORY 2
create a new sighting in the database
[{"id":1,"animal_id":3,"latitude":95.0,"longitude":135.0,"date":"2020-09-10","created_at":"2022-12-13T23:38:43.732Z","updated_at":"2022-12-13T23:38:43.732Z"}]

Update a sighting in the database - change latitude
[{"id":1,"animal_id":3,"latitude":20.0,"longitude":100.0,"date":"2020-09-10","created_at":"2022-12-13T23:38:43.732Z","updated_at":"2022-12-14T00:05:09.791Z"}

Delete a sighting in the database
Deleted
{"id":2,"animal_id":3,"latitude":50.0,"longitude":200.0,"date":"2022-05-10","created_at":"2022-12-14T00:09:08.700Z","updated_at":"2022-12-14T00:09:08.700Z"}]
