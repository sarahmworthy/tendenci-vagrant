# Tendenci Vagrant

Run Tendenci locally with access to edit addons and themes via vagrant and Virtualbox.

## Requirements

You will need the following software installed to use the tendenci vagrant virtualbox:

- Virtualbox (https://www.virtualbox.org/wiki/Downloads)
- Vagrant (http://www.vagrantup.com/)

## Installation and Use

From the command line, clone this repo and then cd into the folder:

    git clone git@github.com:tendenci/tendenci-vagrant.git
    cd tendenci-vagrant

Next, launch the virtualbox with vagrant. The **first** run will download the box (700+ mb), so it may take a few minutes. Once downloaded, subsequent uses of `vagrant up` can be run in under a minute.

    vagrant up

This will start a server. Travel to http://127.0.0.1:8080 in your browser to use the Tendenci site. You can use `admin` as the username and password to the Tendenci site at http://127.0.0.1:8080/login/.

To edit themes or add a new theme, please see the files in the tendenci-vagrant/themes folder. You can add additional themes that can be downloaded from https://github.com/tendenci/tendenci-themes
