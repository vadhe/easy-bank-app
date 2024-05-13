# README

## initial setup

```bash
pnpm install
```

### setup strapi

```
cd packages/easy-bank-api/
cp .env.example .env
pnpm run strapi import -f easy-bank-data.tar.gz
```

### setup astro

```
cd packages/easy-bank/
cp .env.example .env
```

### running local dev

```
pnpm start
```

### type generating from strapi 

```
pnpm generated:type
```