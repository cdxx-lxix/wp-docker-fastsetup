## W🤮rdpress
Setup your disgusting wordpress installation fast (without phpmyadmin).
You need:
Docker
Git
Some text editor eg. Nano

### Commands

###### Clone the repo

``` sudo git clone https://github.com/cdxx-lxix/wp-docker-fastsetup.git ```

###### Start the containers

undetached mode
``` sudo docker-compose up ```

detached mode
``` sudo docker-compose up -d ```

### Configurations

The whole wordpress will be available in the same folder as this cloned repo
Installation uses php.ini from 'config' folder (beware some settings aren't default)
