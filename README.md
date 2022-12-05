Submitted By: Maryam Saleem

Modified Files:
1. Http/Controllers/inventoryController.php
2. routes/api.php
3. database/seeders/inventorySeeder.php
4. app/Http/Requests/storeInventoryRequest.php
5. app/Models/inventory.php
6. database/migrations/2022_12_05_100217_create__inventory__table.php

Database Name = Task5
Table Name = inventory

------------------- Routes ------------------- 
1. Read entire inventory: http://127.0.0.1:8000/api/inventory    (Method = GET)
2. Read an item using id: http://127.0.0.1:8000/api/inventory/(id)     (Method = GET)
3. Insert an item: http://127.0.0.1:8000/api/inventory/insert    (Method = POST)  ------- (set key = Accept and value = application/json in header in postman)
4. Update an item using id: http://127.0.0.1:8000/api/inventory/update/(id)     (Method = PUT or POST)
5. Delete an item using id: http://127.0.0.1:8000/api/inventory/delete/(id)     (Method = DELETE or POST)
