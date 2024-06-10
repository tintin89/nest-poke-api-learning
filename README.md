<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run on Development
1. Clone the repo
2. Run
```
npm install
```
3. You must have @nestjs/cli installed
```
npm install -g @nestjs/cli
```

4. Start Database
```
docker-compose up -d
```

5. Insert Seed into BD running a "Get" request to this endpoint
```
http://localhost:3000/api/v2/seed
```


## Tech Stack
* MongoDB
* Nest