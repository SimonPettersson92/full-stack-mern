# Full stack MERN

A small full stack application using the MERN (Mongo, Express, React, Node) stack. The user can enter data into a table, which is then stored in a MongoDB database and displayed at the top of the page. The data can also be updated and deleted. Thanks to React, the page is updated without a reload.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

An installation of node.js is needed to run the application. Node.js can be found at

```
https://nodejs.org/en/download/
```

A MongoDB database is also needed, locally or remotely. Enter the connection key in the environment file or directly in backend/server.js.

### Installing

With node.js installed and the database set up run

```
npm install
```

to install all dependencies. Then run

```
npm start
```

to run the application locally.

### Preview

The page should look like this when starting the application, with no data in the database.

![alt text](https://i.postimg.cc/KYnYrq2H/startpage.png)

After adding an item, the item's id and data are shown at the top.

![alt text](https://i.postimg.cc/KzRnYhLM/first-item.png)

The data of the item can then be modified using the unique id.

![alt text](https://i.postimg.cc/SR4NvWyx/modified.png)

In addition, other items can also be added and deleted.
