
# Backendutveckling och API:er #2: Använda MongoDB i Node.js med Express.js och Handlebars

👋 Se Linus Rudbecks föreläsning från 10 april ✅ 

### Innehåll denna workshop:

* Kunskap om dokumentdatabsen MongoDB (NoSQL)
* Skriva CRUD för flera resurser mot en MongoDB databas med MongoDB Node.js Driver 

### Redovisning:
* Du redovisar resultatet av sida för en eller flera resurser med CRUD

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***

# 👩🏽‍💻 Övning: Skapa en webbapplikation med databashantering av minst 2 st valfria resurser

Syftet med övningen är att applicera CRUD (Create, Read, Update, Delete) mot en MongoDB-databas i en Node.js/Express.js/Handlebars webbapplikation.

Installera/tillgång till MongoDB [https://www.mongodb.com/](https://www.mongodb.com/) (två alternativ)

* Installera databasen lokalt med MongoDB Community Server (kan vara problem på Mac)
* Molnbaserad lösning, MongoDB Atlas

Du kan också ladda ner MongoDB Compass som ett GUI för att hantera din databas, men det går också bra att monitorera i MongoDB Atlas.

För att koppla upp och använda funktioner mot databasen använder du
MongodDB Node.js Driver:

* Officiel dokumentation: [https://www.npmjs.com/package/mongodb](https://www.w3schools.com/nodejs/nodejs_mongodb.asp)
* Alternativ dokumentaion: [https://www.w3schools.com/nodejs/nodejs_mongodb.asp](https://www.w3schools.com/nodejs/nodejs_mongodb.asp)

### 👉 Din uppgift

**Utgå från förra workshopen samt Linus senaste föreläsning!**

Skapa en webbapplikation med Node.js, Express.js, MongoDB och Handlebars som ger användaren möjligheten att skapa, läsa, uppdatera av olika resurser. Du väljer resurser själv, men det kan exempelvis vara:

* Användare och inlägg
* Böcker och tidningar
* Resmål och kommentarer
* Låtlista, låtar och artister

Försök att jobba själv från grunden och använd inte bilar som i Linus exempel 🙂 


# 👩🏽‍💻 Bonus: Mer funktionalitet med MongoDB

Prova andra funktioner utöver CRUD från MongoDB, som:

* Använda Query
* Skapa pagination med Limit
* Sortera baserad på datum då ett fält skapates/uppdaterades
* Använd Join som matcha två olika colletions

Du väljer själv vad som passar din webbapplikation!


# 💬 Diskutera/Bra att kunna

Allmänt om databaser:

* Vad är en NoSQL databas? Ge exempel.
* Vad är en SQL databas? Ge exempel.
* När är det fördel att använda en NoSQL databas framför en SQL databas? Och när är en SQL databas att föredra en NoSQL databas?
* Vilken typ av NoSQL databas är MongdoDB? Vad finns det för andra NoSQL databaser?
* Vad menas med CRUD?

MongoDB:

* Vad är databas - kollektion - dokument - fält i en dokumentdatabas?

Övrigt:

* Vad är HTTP-metoderna för CRUD? Vilken metod(route) använder man i Express.js för att skicka från formulär?
* Vad är req.body?
* Vad gör body-parser?
* Hur kan man få ta tag i url-parameters med Express.js?

**Och kom ihåg, commita aldrig din connection-string eftersom den innehåller lösenord!**
För att spara config-uppgifter kan en dotenv-fil användas, [se här](https://www.freecodecamp.org/news/how-to-use-node-environment-variables-with-a-dotenv-file-for-node-js-and-npm/). 
