# Development

```bash
git clone git@github.com:nocobase/nocobase.git app
cp .env.example
docker-compose up -d
docker-compose run app bash -c 'npm install && npm run bootstrap && npm run build && npm run db-migrate init'
docker-compose up -d
```
