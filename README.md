# Blog API Application Project

Build a Blog API that can be used to manage posts and comments as well as go through the registration and logging user process using a JWT token

## Tech Stack

**Server:** Node, Express, MongoDB, Mongoose, JWT

# API FEATURES

- ✅ Authentication using JSON Web tokens (JWT) & Authorization
- ✅ Post CRUD operations
- ✅ Category CRUD operations
- ✅ Comment functionality
- ✅ Profile photo uploaded
- ✅ Update password
- ✅ System blocking user if inactive for 30 days
- ✅ Admin can block a user
- ✅ A user can block different users
- ✅ A user who block another user cannot see his/her posts
- ✅ Check if a user is active or not
- ✅ Check last date a user was active
- ✅ Changing user award base on number of posts created by the user
- ✅ A user can follow and unfollow another user
- ✅ Get all users who views someone's profile
- ✅ Admin can unblock a blocked user
- ✅ A user can close his/her account

</br>
</br>

![blogAPI](https://user-images.githubusercontent.com/82850895/215177113-97ec1687-c513-4b87-af33-bf98a25ae2a1.png)

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run server
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`MONGODB_URL` , `JWT_SECRET` , `CLOUDINARY_CLOUD_NAME` , `CLOUDINARY_API_KEY` , `CLOUDINARY_API_KEY` , `CLOUDINARY_API_SECRET_KEY`

##### BaseURL = `https://test.onrender.com/`

# API Authentication

Some endpoints may require authentication for example. To create a create/delete/update post, you need to register your API client and obtain an access token.

The endpoints that require authentication expect a bearer token sent in the `Authorization header`.

**Example**:

`Authorization: Bearer YOUR TOKEN`
