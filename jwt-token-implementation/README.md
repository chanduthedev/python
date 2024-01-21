# Json Web Token implementation in python

### Setup

##### Step 0: Virtual Environment setup

- Create virtual environment

  `python3 -m venv folder_name`

- Enable virtual environment

  `source folder_name/bin/activate`

##### Step 1: Install dependencies

- Install dependencies by running below command

  `pip3 install -r requirments.txt`

##### Step 2: start the server

- Start the server by running below command

  `python3 app.py`

### Testing:

- Send post request with body as below

  `{
"user_name": "test",
"password": "test"
}
`

- Expected response would be something like below

  `
{
  "data": {
      "token":
      "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX25hbWUiOiJ0ZXN0IiwiZXhwIjoxNzA1ODM1NjU4fQ.MkEwy5EuQrj5RvaoWKlqogCN3cMMql60N4xL3whwLfc",
      "user_name": "test"
    },    
    "message": "User login successfully"
}`
