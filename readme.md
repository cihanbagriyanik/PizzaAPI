# PIZZA API

### ERD:

![ERD](./erdPizzaAPI.png)

### Folder/File Structure:

```
    logs/
    src/
        configs/
            dbConnection.js
            swagger.json
        controllers/
            auth.js
            order.js
            pizza.js
            token.js
            topping.js
            user.js
        helpers/
            passwordEncrypt.js
            sendMail.js
            sync.js
        middlewares/
            authentication.js
            errorHandler.js
            findSearchSortPage.js
            logger.js
            permissions.js
        models/
            order.js
            pizza.js
            token.js
            topping.js
            user.js
        routes/
            auth.js
            document.js
            order.js
            pizza.js
            token.js
            topping.js
            user.js
    .env
    .gitignore
    index.js
    package.json
    readme.md
    swaggerAutogen.js

```
