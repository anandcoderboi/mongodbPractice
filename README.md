## mongodbPractice
# db.students.find() ![ss1](https://user-images.githubusercontent.com/49033626/206903808-4b5309c0-1d5d-4dc6-a045-933daa886ef2.png)
# db.students.find({gender:{$in:["Male","Bigender"]}}) ![ss2](https://user-images.githubusercontent.com/49033626/206903811-9641a1d9-012f-4f1f-9ec3-ae6a65e29792.png)
# db.inventory.find({status:"D"}) ![ss4](https://user-images.githubusercontent.com/49033626/206904856-095826a9-b356-46a7-aeca-d6db95f46c65.png)
# db.inventory.find({status:{$In:["A","D"]}}] ![SS5](https://user-images.githubusercontent.com/49033626/206903816-a7897d92-4a7f-490e-81b7-75c8162acc50.png)
# db.inventory.find({status:"A",qty:{$lt:50}}) ![ss6](https://user-images.githubusercontent.com/49033626/206903818-d3edc4a9-9266-4401-a945-6567ef66e1f8.png)
# db.inventory.find({"size.uom":"cm"}) ![ss8](https://user-images.githubusercontent.com/49033626/206903821-a23e5b94-35ed-478d-b5a4-bf39b6f24856.png)
# db.inventory.find({"size.uom":"cm","size.h":{$lt:20}}) ![ss9](https://user-images.githubusercontent.com/49033626/206903822-2d2a2b54-d8d9-401f-ac4a-3abb10a4d16d.png)
# db.inventory.find({tags:["red","blank"]}) ![ss10](https://user-images.githubusercontent.com/49033626/206903824-28869212-f6b1-43df-bdad-a514f53f5a73.png)
# db.inventory.find(){tags:{$all:["red","blank"]}} ![ss11](https://user-images.githubusercontent.com/49033626/206903825-07efee41-72a2-4bc5-b1fe-8db50d3886a1.png)
![ss12](https://user-images.githubusercontent.com/49033626/206903827-38e039a7-30b3-468d-9ce3-4dd742cbed67.png)
![ss13](https://user-images.githubusercontent.com/49033626/206903829-45cf9576-1e66-4ef4-9d1b-4ffd3f45c923.png)
![ss14](https://user-images.githubusercontent.com/49033626/206903832-c20566c4-7310-44c1-8d49-d8b21d7c8f3a.png)

