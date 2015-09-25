![blazing-squirrel](public/images/bs.png)
# Blazing Squirrel #
io.js + HTML5 SQL client

## Linux Install:
+ Download CLI driver
+ on Linux, install unixodbc and git:
```sh
apt-get install iojs npm git unixodbc unixodbc-dev -y
```
+ create a [BLAZING_SQUIRREL] driver in `odbcinst.ini` ([example](examples/linux/odbcinst.ini))
+ then:
```sh
git clone https://github.com/LeoDutra/blazing-squirrel.git
cd blazing-squirrel
npm install
npm start
```
+ go to [http://localhost:3000]()

## PM2 - Making a "phoenosquirrel" ( phoenix + squirrel (⌐■_■) )
Optionally you use BlazingSquirrel with [PM2](http://pm2.keymetrics.io/), running pm2.sh,
so it will restart automatically after failures and system reboot.

## Using the FreeTDS ODBC driver
[Go to node-odbc's FreeTDS driver reference](https://github.com/wankdanker/node-odbc#using-the-freetds-odbc-driver)