## Important Setups
### 0. Install MongoDB on your server
### 1. Start MongoDB service
```
systemctl mongod
```
### 2. Install JS packages and initialize MongoDB
```
npm install
mongo hotel scripts/init.mongo.js
```
This will create "hotel" database and tow collections "customer" and "counters" in it.
> **Note:** this project accesses hotel->customers and hotel->counters in MongoDB. 

### 3. Start the server
```
npm start
```

### 4. Compile JSX file to JS file in *ui* folder in a new shell
```
npx babel src --out-dir public
```

### 5. The MongoDB CRUD test script can be executed by
```
node scripts/trymongo.js
```
All information will be printed in console.
