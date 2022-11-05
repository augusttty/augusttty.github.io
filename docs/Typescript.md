---
link: https://anomanm.notion.site/Typescript-e82a7775546940698e54d09ebb63e9e9
notionID: e82a7775-5469-4069-8e54-d09ebb63e9e9
---
# How to create a new instance using interface🤣

```
interface IStudent {
      Id: number;
      name: string;
    }

Method 1. all fields must assign data.
 const  obj1: IStudent = { Id: 1, name: 'Naveed' };

Method 2. my favorite one
const obj2 = { name: 'Naveed' } as IStudent ;

Method 3.
const obj3 = <IStudent >{name: 'Naveed'};

Method 4. use partial interface if all fields not required.
const  obj4: Partial<IStudent > = { name: 'Naveed' };

Method 5. use ? Mark with interface fields if all fields not required.
const  obj5: IStudent = {  name: 'Naveed' };
```