# env_files

## convention

- `<service>.<mode>.env`

### backend.dev.env

```env
MONGO_URL="mongodb://admin:1205@mongo:27017"
```

### frontend.dev.env

```env

```

### mongo.dev.env

```env
MONGO_INITDB_ROOT_USERNAME=admin
MONGO_INITDB_ROOT_PASSWORD="1205"
```

### mongoadmin.dev.env

```env
ME_CONFIG_MONGODB_ENABLE_ADMIN: "true"
ME_CONFIG_MONGODB_URL: "mongodb://admin:1205@mongo:27017"
ME_CONFIG_OPTIONS_EDITORTHEMEL: "material"
ME_CONFIG_BASICAUTH_USERNAME=admin
ME_CONFIG_BASICAUTH_PASSWORD=me1205
ME_CONFIG_SITE_COOKIESECRET=cookiesecret
ME_CONFIG_SITE_SESSIONSECRET=sessionsecret
```
