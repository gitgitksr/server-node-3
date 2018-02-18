# Nodejs HAPI Sample Server

A [HAPI](https://github.com/hapi-server/data-specification/) 2.0 server implemented in [node.js](http://node.js) intended for testing [HAPI clients](https://github.com/hapi-server/data-specification/).

Serves code-generated [parameters](https://github.com/hapi-server/nodejs-server/blob/master/parameters.js) of most types allowed by the [HAPI specification](https://github.com/hapi-server/data-specification/).

A running instance of this server is available at [http://mag.gmu.edu/hapi](http://mag.gmu.edu/hapi).

Software for a full-featured HAPI server, [TSDS](http://tsds.org/), is available at [http://github.org/tsds/tsds2](http://github.org/tsds/tsds2).  If you would like to use [TSDS](http://tsds.org/) to make your data server or file-based data set HAPI compliant without developing your own server, contact <rweigel@gmu.edu>.  

# Installation

Install [nodejs](https://nodejs.org/en/download/) (tested with v7.10.0) and then

```bash
git clone https://github.com/hapi-server/server-nodejs
cd nodejs-server; npm install
node server.js --port 8999
```

Open http://localhost:8999/hapi in a web browser.

# Unit Tests

To run unit tests (executes `test` target in `package.json`)

```
npm test
```

# Sample Requests

See [tests.sh](https://github.com/hapi-server/nodejs-server/blob/master/tests.sh) in <code>./nodejs-server</code>.

# Contact

Bob Weigel <rweigel@gmu.edu>.