# sails-hook-model-indexes
> Advanced indexing support for models in Sails.js / Waterline

---

Goals:
- [ ] Support complex indexes that are applied to multiple model fields and advanced options
- [ ] Support multiple Sails/Waterline adapters
  - [ ] [MongoDB - sails-mongo](https://github.com/balderdashy/sails-mongo)
  - [ ] [MySQL - sails-mysql](https://github.com/balderdashy/sails-mysql)
  - [ ] [PostgreSQL - sails-postgresql](https://github.com/balderdashy/sails-postgresql)
  - [ ] Easily be able to add more supported adapters!
- [ ] Common interface for all supported adapters
  - Do not write adapter-specific code for indexing!
  - Switch between MongoDB, MySQL, PostgreSQL, and more and apply your indexing without changing anything except your adapter configuration!
