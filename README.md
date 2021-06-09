# find-command-with-dir-excluded
Unix/Linux/mac "find" command line with directories excluded

find all .js files, exclude the files from this directory: node_modules, config and .vscode :
```
find . -name "*.js" | egrep -v "node_modules|config|.vscode"
```

sample output : 
```
./app/middlewares/idx.js
./app/middlewares/aut.js
./app/middlewares/sgn.js
./app/middlewares/lgin.js
./app/models/skp.model.js
./app/models/ir.model.js
./app/models/rls.model.js
./app/models/idx.js
./app/models/skpmnt.model.js
./app/models/skpcls.model.js
./app/models/tst.model.js
./app/models/usr.model.js
./app/models/uk.model.js
./app/models/skpd.model.js
./app/models/act.model.js
./app/models/tk.model.js
./app/models/pydk.model.js
./app/models/emp.model.js
./app/models/skpcnf.model.js
./app/models/skptbh.model.js
./app/controllers/tk.controller.js
./app/controllers/tst.controller.js
./app/controllers/aut.controller.js
./app/controllers/mnu.controller.js
./app/controllers/rvw.controller.js
./app/controllers/emp.controller.js
./app/controllers/usr.controller.js
./app/routes/emp.routes.js
./app/routes/mnu.routes.js
./app/routes/aut.routes.js
./app/routes/rvw.routes.js
./app/routes/usr.routes.js
./app/routes/tk.routes.js
./idx.js
```
