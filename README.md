# Amazon RDS Certificates for Node

This package provides all Amazon RDS certificates in use between 2010 and 2024.
It's a convenience package allowing you to ensure the highest security levels without having to ship certificates in your own project.

## Install

```
npm install rds-ca
```

## Usage

```
const options = {
  host,
  user,
  password,
  database,
  ssl: {
    ca: require('rds-ca')
  }
}
```

# Credits

Inspired by the [`mysql` package's inclusion of the same certificates](https://github.com/mysqljs/mysql/blob/v2.18.1/lib/protocol/constants/ssl_profiles.js) and
[@toriihq's `mysql-rds-ca` package](https://github.com/toriihq/mysql-rds-ca).

# License

MIT
