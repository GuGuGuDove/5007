# Hotel California International

Important Setups:
1. Start mongodb service: 
    systemctl mongod
2. Run initial mongo script: this will create "hotel" database and tow collections "customer" and "counters" collections in it.
    mongo hotel scripts/init.mongo.js
3. Start server:
    npm start
4. Always remember this project accesses hotel-customer and hotel-counters in mongodb.
5. The Mongdb CRUD test script can be executed by:
    node scripts/trymongo.js (All information will be printed in console.)  
