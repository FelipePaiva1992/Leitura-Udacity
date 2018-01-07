# Udacity Leitura

`Leitura` project of React Nanodegree - Udacity

## Who to Execute the API
* Install and start the API server
    - `cd api-server`
    - `npm install`
    - `node server`


## Who to Execute the Project
* Install and start the Project ( in a new terminal tab )
    - `npm install`
    - `npm start`

## What You're Getting
```bash
├── README.md - This file.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── api-server # The project api server, run before of start the project
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── index.js # This is the root of your app. Contains static HTML right now.
    ├── actions # Actions of the application
    │   ├── ActionsTypes.js # List of type actions
    │   ├── PostActions.js
    │   ├── PostDetailActions.js
    │   └── RootActions.js
    ├── components # Scenes of the application
    │   ├── index.js
    │   ├── Categories.js
    │   ├── Commentary.js
    │   ├── If.js
    │   ├── ListPosts.js
    │   └── MenuNavTop.js
    ├── entities # Entities of the application
    │   ├── index.js
    │   ├── CategoryEntity.js
    │   ├── CommentEntity.js
    │   └── PostEntity.js
    ├── reducers # Reducers of the application
    │   ├── index.js
    │   ├── PostDetailReducer.js
    │   ├── PostReducer.js
    │   └── RootReducer.js
    ├── router # Router of the application
    │   └── index.js
    ├── store # Store(Redux) of the application
    │   └── index.js
    ├── style # Application Styles
    │   ├── index.js
    │   ├── FormPostStyle.js
    │   ├── ListPostsStyle.js
    │   └── MenuNavTopStyle.js
    ├── util
    │   └── api.js # A JavaScript API for the provided Udacity backend.
    ├── views
    │   ├── comment
    │   │   └── CommentFormView.js    
    │   ├── post
    │   │   ├── PostDetailView.js
    │   │   └── PostFormView.js
    │   └── root
    │       └── RootView.js
    └── index.js # You should not need to modify this file. It is used for DOM rendering only.
```
