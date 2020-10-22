

# CodeWitUs

> SEER Labs


## Technology Stack

> Back-End

- Ruby on Rails
- MySQL

> Front-End

- HTML
- CSS
- BootStrap
- JavaScript
- jQuery
- AJAX


## Requirement 

> Rails and GEM

- Rails version             6.0.3.3
- Ruby version              ruby 2.7.0
- RubyGems version          3.1.4
- Rack version              2.2.3
- Database Adapter          mysql2
- Omniauth-google-oauth2 (0.8.0)

> Database
- MYSQL Ver 8.0.21



## Installation

- All the `code` required to get started

### Clone

- Clone this repo to your local machine using `git clone https://github.com/kbuffardi/CodeWitUs.git`

```shell
$ cd CodeWitUs
```

### Set Google OAuth API Credentials

> Google OAuth
- Create a .env file in the root directory of your app.
-  Add the following code to the file.
`GOOGLE_CLIENT_ID=Your client id  `
`GOOGLE_CLIENT_SECRET=Your client secret`


### Setup

> Now Install all project requirements
```shell
$ bundle install
```

> Now create database, migrate database

> Make changes in `config/database.yml` file and set your SQL database credentials.


```shell
$ rails db:create
```

```shell
$ rails db:migrate
```

> Now `Start Server`

```shell
$ rails s
```


> Brower

```shell
  http://localhost:3000/login
```


## Contributing

> To get started.

- 🍴 Fork this repo!

- 💻 Clone this repo to your local machine using `https://github.com/kbuffardi/CodeWitUs.git`

- 🔃 Create a new pull request using <a href="https://github.com/kbuffardi/CodeWitUs.git" target="_blank">`https://github.com/kbuffardi/CodeWitUs`</a>.

