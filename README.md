# Message Board

[![status|done](http://jeffreynerona.com/badges/status-done.svg)](http://jeffreynerona.com/projects) [![type|practice-project](http://jeffreynerona.com/badges/type-practiceproject.svg)](http://jeffreynerona.com/projects/) [![language|ruby](http://jeffreynerona.com/badges/language-ruby.svg)](http://jeffreynerona.com/projects/javascript)  [![type|practice-project](http://jeffreynerona.com/badges/technology-rubyonrails.svg)](http://jeffreynerona.com/projects/)

A simple message board application using Ruby On Rails. 

![jeffreynerona|photobard](https://raw.githubusercontent.com/jeffreynerona/message_board/master/screenshot/messageboard.png)

# Features

  - Login and Register
  - Create, View, Update, and Delete Post
  - Create, View, Update, and Delete Comments

# Gems Used

  - boostrap-sass
  - simple_form
  - devise
  - pg

# Installation
Make a project folder then open it:
```sh
$ mkdir messageboard && cd messageboard
```

Clone Repository:
```sh
$ git clone git@github.com:jeffreynerona/message_board.git
```

Install dependencies:
```sh
$ bundle install
```

Migrate Database:
```sh
$ rake db:migrate
```

Run the server:
```sh
$ rails s
```

