<p>
<img width="260" height="170" src="https://xxx" align="right" >
</p>


### `models/`

- `base.py`: base of all models of the API - handle serialization to file
- `user.py`: user model

## Setup

```
$ pip3 install -r requirements.txt
- requests
- flask
- pycodestyle2.5
```

## Run

```
$ ython3.7 ./app.py
```

## Routes

- `GET /`: Index
- `POST /users`: Register user {email: email, password: password}
- `POST /sessions`: Logged Post {email: email, password: password}
- `DELETE /sessions`: Destroy session
- `GET /profile`: Get user profile {session_id: 2345676543sdfghjgfd}
- `PUT /reset_password`: Reset the password {"email": email, "reset_token": token, "new_password": new_pwd}

## Files

| Files          | Description            |
| -------------- | ---------------------- |
| **0-main.py**  | User Initial           |
| **user.py**    | User model             |
| **1-main.py**  | Add user               |
| **2-main.py**  | Find user              |
| **3-main.py**  | Update user            |
| **4-main.py**  | Hash Password          |
| **db.py**      | Database methods       |
| **5-main.py**  | Register user          |
| **8-main.py**  | Credentials validation |
| **10-main.py** | Get session ID         |
| **auth.py**    | Authentication         |
| **app.py**     | Principal Main Flask   |
| **main.py**    | Test with assert       |
