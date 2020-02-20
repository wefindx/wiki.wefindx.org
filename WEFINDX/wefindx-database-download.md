# WeFindX Database Download

The database combines the data from multiple infinity project servers around the world into a single database. You can connect to the database \(running MongoDB 3.6.2\) by:

---

`mongo --host mongodb://public:data@wefindx.net`

To download all the topics, comments and transactions to work with locally, you can do:

`mongoexport -h wefindx.net:27017 --authenticationDatabase admin -u public -p data -d public -c topics > topics.json`

`mongoexport -h wefindx.net:27017 --authenticationDatabase admin -u public -p data -d public -c comments > comments.json`

`mongoexport -h wefindx.net:27017 --authenticationDatabase admin -u public -p data -d public -c translactions > transactions.json`

---

Please, contact `hello@wefindx.com` for special access to the non-public databases. You may need to sign a non-disclosure agreement to do that.

