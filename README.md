# Ideaboard API

This is a Rails API that includes the data for an Ideaboard application. It includes versioning.

Business information includes:

- title
- body

Users can access:

- GET requests for ideas.
- POST, PATCH, PUT, DELETE requests for ideas.

# Installation

`git clone https://github.com/sowmyadsl/ideaboard-api`
`cd ideaboard-api`

# PostgreSQL Integration

`postgres`
`rake db:create`
`rake db:migrate db:test:prepare`

# Seed database

`rake db:seed`

# Development server

Run `rails s` for a dev server. Navigate to `http:localhost:3000/api/v1/ideas`. The app will automatically reload if you change any of the source files.

# Technologies used

- Ruby
- Rails
- PostgreSQL
- git

# Other sources
* [RACK Cors](https://github.com/cyu/rack-cors)

# Known Bugs
- No known bugs as of now.

# License

This software is licensed under MIT license.

`Copyright (c) 2017 Sowmya Dinavahi`
