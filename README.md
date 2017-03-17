# Environment Workshop

### 1. Enviroment: Getting ready for work
- Create a series of vagrant machines provisioned with ansible
  * Should use `ubuntu/16.04`
  * One machine should have `PHP 7.1`
  * Another machine should have `elastic search`
  * Machine should be inside a `vm` folder with a namespace for the machines group you'll be creating
  
- Now that we have our machines running, we realised we forgot to add a service in the `front` machine (The one with `php`) 
  * We should now update our _playbook_ to also install `nginx`. Do this by doing a re-provision rather than deleting and setting up your machine.
  * Once done, share a folder `src` with your _Vagrantfile_ so you can expose it to your `nginx` and execute an `index.php` file that prints `Hello World`
