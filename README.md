# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: 3.2.2

* Rails: 7.0.7.2

* Configuration
    Packages and dependencies to install for run the project.
    NVM:
        Execute the followings command in your terminal:
            Install NVM:
            ```
                curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
            ```
            Reload your terminal:
            ```
                source ~/.bashrc
            ```
            Install Node:
            ```
                nvm install node
            ```
            Install Latest LTS version:
            ```
                nvm install --lts
            ```
            Use Latest LTS version:
            ```
                nvm use --lts
            ```
            Use Node:
            ```
                nvm use node
            ```
            Set default version:
            ```
                nvm alias default node
            ```
            Verify current NVM Node version:
            ```
                nvm current
            ```
    Yarn:
        Install at Ubuntu 22.04:
        ```
            curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
            echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
            sudo apt update && sudo apt install yarn
        ```
        Verify Yarn version:
        ```
            yarn --version
        ```
    RVM:
        Install GPG keys:
        ```
            gpg2 --keyserver keyserver.ubuntu.com --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
        ```
        Install RVM:
        ```
            curl -sSL https://get.rvm.io | bash -s stable
        ```
        Reload your terminal:
        ```
            source ~/.bashrc
        ```
        Verify RVM version:
        ```
            rvm --version
        ```
        Install Ruby:
        ```
            rvm install ruby
        ```
        Verify Ruby version:
        ```
            ruby --version
        ```
        Set default version:
        ```
            rvm --default use ruby
        ```
    Ruby on Rails:
        Install Rails:
        ```
            gem install rails
        ```
        Verify Rails version:
        ```
            rails --version
        ```

* Install gems:
    ```
        bundle install
    ```

* Run project locally: 
    ```
        rails s
    ```

* Generate migrations
    ```
        rails generate migration <migration_name>
    ```

* Run migrations
    ```
        rails db:migrate
    ```

* Rollback migrations
    ```
        rails db:rollback
    ```

* Use rails console:
    ```
        rails c
    ```

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
