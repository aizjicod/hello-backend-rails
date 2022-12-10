<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Install](#install)
  - [Feed](#feed)
  - [Usage](#usage)
  - [Front-end](#front-end)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# 📖 Hello Back-end Rails <a name="about-project"></a>

> This API-only app displays a random greeting message. It is considered the back-end.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

- Ruby & PostgreSQL
- Ruby on Rails
- Linters (Rubocop & Stylelint)
- Git & GitHub

## 💻 Getting Started <a name="getting-started"></a>

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
### Done!

Ready to work?⛏️ You're all set to explore and change the repo locally (on your computer).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Alejandro torres**

- GitHub: [@githubhandle](https://github.com/aizjicod)
- Twitter: [@twitterhandle](https://twitter.com/aizijijr)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/aiziji/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Microverse.
- Google and Stack Overflow.
- Inspiration.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

