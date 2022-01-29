# Bhopmaps - API (v2)

## Enpoints
```
POST /maps - create new map
PATCH /maps/:id - edit map
GET /maps - list maps
GET /maps/:mapname - list specific map

POST /user - create new user
PATCH /user - edit user
GET /user - get information about logged in user
GET /user/:username - get user information
GET /user/:username/maps - list user's maps

POST /auth - log in
DEL /auth - log out
```
## .env.local
```
# Database (mysql)
DB_USER=
DB_PORT=
DB_HOST=
DB_PW=
DB_NAME=

# AWS S3
S3_ACCESS=
S3_SECRET=
S3_REGION=
S3_BUCKET=

# JWT
JWT_SECRET=

# OTHER
ORIGIN_URL=
```
