yarn dev
    Starts the development server.

  yarn build
    Builds the app for production.

  yarn start
    Runs the built app in production mode.

## Folder Structure

![folder_structure](./docs/folder_structure.jpeg)

## URLs

* APP Next Client : http://localhost:3000/

* Sanity data schema : http://localhost:3333

## Sanity

sanity init --coupon cleverprogrammer

sanity start

############ 

sanity.json

{
  "root": true,
  "project": {
    "name": "govinda_ecomm"
  },
  "api": {
    "projectId": "2qgkdnqw",
    "dataset": "production"
  },
  "plugins": [
    "@sanity/base",
    "@sanity/default-layout",
    "@sanity/default-login",
    "@sanity/desk-tool"
  ],
  "env": {
    "development": {
      "plugins": [
        "@sanity/vision"
      ]
    }
  },
  "parts": [
    {
      "name": "part:@sanity/base/schema",
      "path": "./schemas/schema"
    }
  ]
}