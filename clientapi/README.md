# clientapi

a [Sails](http://sailsjs.org) application

```console
$ npm install -g sails
$ sails new clientapi
$ cd clientapi
$ sails generate api users
$ sails lift
prompt: ?: 2

info: Server lifted in `C:\Git\sm\clientapi`
info: To see your app, visit http://localhost:1337
info: To shut down Sails, press <CTRL> + C at any time.
```

### Sails Blueprint

Routes | Param
--- | ---
localhost:1337/users/Create | ?<key>=<value>&<another_key>=<another_value>
localhost:1337/users/update/<id> | ?<key>=<value>&<another_key>=<another_value>
