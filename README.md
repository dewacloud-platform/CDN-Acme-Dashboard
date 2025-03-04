## Dewacloud Academy Node.js Deployment Hands On

Original source: [Next Learn](https://nextjs.org/learn)

### Getting Started

1. **Install dependencies**
```
cd cdnx-2
npm install
```

2. **Create .env**
```
cp .env.example .env
```

3. **Populate .env**: Create database connection string using database credentials

4. **Start the server**
#### Development
```
npm run dev
```
#### Production
```
npm run build
npm run start
```

5. **Seed database**: Navigate to https://[host]/seed