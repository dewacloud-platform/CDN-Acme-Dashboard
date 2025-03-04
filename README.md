## Dewacloud Academy Node.js Deployment Hands On

Original source: [Next Learn](https://nextjs.org/learn)

### Getting Started

1. **Install dependencies**
```
cd cdnx-2
npm install
```

2. **Fill ecosystem.config.js file with the appropriate configurations**

3. **Create .env**
```
cp .env.example .env
```

4. **Populate .env**: Create database connection string using database credentials

5. **Seed database**
```
npm run seed
```

5. **Start the server**
#### Development
```
npm run dev
```
#### Production
```
npm run build
npm run start
```