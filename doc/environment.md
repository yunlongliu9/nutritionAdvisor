Runtime:
+ Node.js & npm (**LTS (Long Term Support)** version suggested)
	+ nvm suggested
+ Typescript
Database:
+ PostgreSQL Server(docker suggested)
+ Prisma ORM
Developer tools:
+ VSCode
	+ ESLint: validation check
	+ Prettier: Format automate validation
	+ Prisma: ".prisma" highlight
	+ [Optional] Tailwind CSS IntelliSense
+ DB GUI:
	+ DBeaver
+ Git

# PostgreSQL docker:
1. download docker desktop version 
2. docker run --name my-postgres -e POSTGRES_PASSWORD=YOURPASSWORD -p 5432:5432 -d postgres
3. docker ps  to see whether it is downloaded successfully or not;

# DBeaver connection our PostgreSQL
Parameters:
- **Host:** `localhost`
- **Port:** `5432`
- **User:** `postgres`
- **Password:** `your_password` 
- **Database:** `postgres` 
