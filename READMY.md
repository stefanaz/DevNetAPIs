# API structure:

## Users & Auth:

- Register User **[POST, /api/users]**
- Get Auth User **[GET, /api/auth]**
- Login User **[POST, /api/auth]**

## Profiles:

- Create/Update Profile **[POST, /api/profile]**
- Get logged in users profile **[GET, /api/profile/me]**
- Get all Profiles **[GET, /api/profile]**
- Get Profile by UserId **[GET, /api/profile/user/:user_id]**
- Delete Profile and User **[DELETE, /api/profile]**
- Delete Profile Experience **[DELETE, /api/profile/experience/:experience_id]**
- Delete Profile Education **[DELETE, /api/profile/education/:education_id]**
- Add Experience **[PUT, /api/profile/expericence]**
- Add Education **[PUT, /api/profile/education]**
- Get GitHub Profiles **[GET, /api/profile/github/:githubloginname]**

## Posts:

- Create Post **[POST, /api/posts]**
- Get All Posts **[GET, /api/posts]**
- Get Post By ID **[GET, /api/posts/:post_id]**
- Delete Post **[DELETE, /api/posts/:post_id]**
- Like Post **[PUT, /api/posts/like/:post_id]**
- UnLike Post **[PUT, /api/posts/unlike/:post_id]**
- Add Comment to a Post **[POST, /api/posts/comment/:post_id]**
- Delete Comment from Post **[DELETE, /api/posts/comment/:post_id]/:comment_id]**

# Tech Info:

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm run start`

Runs server side without checking changes. Server side is http://localhost:5000

### `npm run server`

Runs server side with checking changes. Using **nodemone** package.
