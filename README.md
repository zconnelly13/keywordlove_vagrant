Keyword Love Vagrant
====================

1. Download and install vagrant https://www.vagrantup.com/downloads.html as well as virtualbox https://www.virtualbox.org/wiki/Downloads

2. Clone this repository

3. `vagrant up --provider virtualbox && vagrant ssh`

4. `sudo adduser <username>`

5. `sudo adduser <username> sudo`

6. `sudo su <username>`

7. Install your dotfiles

8. update mirror list `sudo apt-get update`

9. install git `sudo apt-get install git`

10. install pip `sudo apt-get install python-pip`

11. install virtualenv `sudo pip install virtualenv`

12. install python-dev `sudo apt-get install python-dev`

13. install libffi-dev (for bcrypt) `sudo apt-get install libffi-dev`

14. Uncomment the following lines
    ```
      # config.ssh.username = ENV['USER'] 
      # config.ssh.private_key_path = '~/.ssh/id_rsa'
      # config.ssh.forward_agent = true
    ```

15. follow the instructions in the keywordlove readme https://github.com/zconnelly13/keywordlove
