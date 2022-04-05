
## Query
```
  const result = await prisma.user.findMany();
```


## Create
```
const result = await prisma.user.create({
    data:{
      email:'bbb@gmail.com'
    }
  });
```


## Upate
```
  const result = await prisma.user.update({
    where:{
      email:'bbb@gmail.com'
    },
    data:{
      name:'bbb'
    }
  });
```