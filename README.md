Lakasir™

![gambar](https://user-images.githubusercontent.com/87823530/127535662-9ea858bd-8c90-429e-bdcf-486662d56110.png)


Lakasir
About Lakasir

Lakasir is a free, open source and online Point Of Sale Software designed for small shop or retail. It is built with modern technologies such as Laravel, VueJS, Bootstrap 4, RESTful API etc.
Requirements

    PHP 7.4 or higher
    Database (eg: MySQL, PostgresSql)
    Web Server (eg: Nginx)
    Other Libraries: development

Framework

Lakasir uses Laravel, the best existing PHP framework, as the foundation framework and Module package for Apps.
Installation

    Install Composer and Npm
    Clone the repository: git clone https://github.com/lakasir/lakasir.git
    Or use composer create-project lakasir/lakasir your-project-name
    access the local domain localhost/install
    fill in several needs such as database and account
    go to terminal and run php artisan migrate; php artisan passport:install;
    Install dependencies: npm install ; npm run dev
    checkout the login url

Installation with docker

    copy .env.example to .env
    change DB_HOST to mysql like this DB_HOST=mysql
    run docker-compose up -d

Contributing

Please, be very clear on your commit messages and pull requests, empty pull request messages may be rejected without reason.

When contributing code to Lakasir, you must follow the PSR coding standards. The golden rule is: Imitate the existing Lakasir code
Ideas

if you want to contribute and add some ideas, please check this link ideas, you can add notes to the ideas card.
Credits

    Sheena Muhammad Ali Zien
    Nasrul Fuad
    Toriq Ahmads

Sponsors

Support Lakasir to becoming a sponsor on Github, Your Profile Picture will show up here with link to your account
License

Lakasir is licensed under MIT License which means it's completely free.
