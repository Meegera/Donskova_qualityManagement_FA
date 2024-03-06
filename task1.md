Семинар 22.02.2024

![image](https://github.com/Meegera/Donskova_qualityManagement_FA/assets/115950487/8775f84b-e170-4317-be3d-17b81c461dc5)

Тесты не проходят из-за версии питона, тк в Python 3.9 нет |
=> изменим код

```
class ObjectCreateOutSchema(BaseModel):
    id: str
    name: Optional[str]
    data: Optional[ObjectData]
    createdAt: str
```

Все тесты пройдены

![image](https://github.com/Meegera/Donskova_qualityManagement_FA/assets/115950487/49689437-1176-4fdd-9b9f-5f71495109a6)

![image](https://github.com/Meegera/Donskova_qualityManagement_FA/assets/115950487/30fb99a2-1e78-4e82-a445-52b7c0705bf6)


<!--![image](https://github.com/Meegera/Donskova_qualityManagement_FA/assets/115950487/a287c01c-e521-481b-9919-ede0b7a00f98)-->
