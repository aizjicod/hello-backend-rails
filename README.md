
# 📖 Hello, world! Back-end

> This API-only app displays a random greeting message. It is considered the back-end.

## 🛠 Built With

- Ruby & PostgreSQL
- Ruby on Rails
- Linters (Rubocop & Stylelint)
- Git & GitHub

## 💻 Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

    Ruby 3.1.2
    PostgreSQL 15.0
    Ruby on Rails 7.0.4

### Setup

    git clone https://github.com/aizjicod/hello-backend-rails.git
    cd hello-backend-rails

### Install

    bundle install
    rails db:create
    rails db:migrate

### Feed

    rails c
    Greeting.create(message: 'Hello, world!')
    Greeting.create(message: '¡Hola mundo!')
    Greeting.create(message: 'Bonjour le monde!')
    Greeting.create(message: 'Hallo Welt!')
    Greeting.create(message: 'Ciao mondo!')
    exit

### Usage

    rails s -p 4000
    make sure this is the port since this will be used on the front-end

Go to [http://localhost:4000/api/v1/greetings](http://localhost:4000/api/v1/greetings) and make sure the messages are visible. Refresh the page to see the different messages.

### Front-end

- [Repository](https://github.com/aizjicod/hello-react-rails-frontend).
- [Pull request](https://github.com/aizjicod/hello-react-rails-frontend/pull/1).

## Authors

👤 **Alejandro torres**

- GitHub: [@githubhandle](https://github.com/aizjicod)
- Twitter: [@twitterhandle](https://twitter.com/aizijijr)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/aiziji/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/aizjicod/hello-backend-rails/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- thanks a lot for microverse since this README file was a template from them, and also for letting me use the template for the mobile skeleton of the portfolio.

## 📝 License

This project is [MIT](MIT.md) licensed.
