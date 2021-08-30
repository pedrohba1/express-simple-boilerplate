## 📝 Content table

- [About](#about)
- [Setup](#getting_started)

## 🧐 About <a name = "about"></a>

NodeJS boiler plate. Comes with sequelize, jest, eslint, prettier and youch.

## 🏁 Setup <a name = "getting_started"></a>

To run this backend you simply need to create a docker container with the following commands:

```
docker run --name umctech -e  POSTGRES_USER=admin -e POSTGRES_PASSWORD=admin -p 5433:5432 -d postgres -e POSTGRES_DB=boilerplate
```

After that, copy the contents of `.env.development` into `.env` and run the migrations with: `yarn sequelize db:migrate`.







