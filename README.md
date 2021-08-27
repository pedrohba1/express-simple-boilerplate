## 📝 Tabela de conteúdos

- [Sobre](#about)
- [Setup](#getting_started)

## 🧐 Sobre <a name = "about"></a>

Backend do UMCtech em nodeJS.

## 🏁 Setup <a name = "getting_started"></a>

Para utilizar esse backend só é preciso criar um container com docker da seguinte maneira:

```
docker run --name umctech -e  POSTGRES_USER=admin -e POSTGRES_PASSWORD=admin -p 5433:5432 -d postgres -e POSTGRES_DB=umctech
```

E em seguida realizar as migrations com `yar sequelize db:migrate`.







