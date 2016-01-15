# indie-brigade-bootstrap

First of all, install [virtualbox](https://www.virtualbox.org/wiki/Downloads) and [vagrant](https://www.vagrantup.com/). While doing this, also download the [box](https://www.dropbox.com/s/x9quvkuukemtbi4/indie-brigade.box?dl=0).

Once this is done, simply run the following commands in the directory you want to install the box in

    $ vagrant box add indie-brigade indie-brigade.box
    $ vagrant init indie-brigade

Once initialized, you are going to replace the generated Vagrantfile by the one contained in this repo. The vagrantfile may need some modification(ask Simon for this). Then:

    $ vagrant up
    $ vagrant ssh

You're in! Once inside the box, you can :

    $ cd indie-brigade
    $ vmrails

To run the app. On your machine(the host), you can type something like http://localhost:8080 in a browser to send a request to the app.

Good work!
