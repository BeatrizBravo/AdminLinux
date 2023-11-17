# Intro

In this lab, we'll go over I/O redirection, file permissions, and using the **ssh** tool. 


## Scenery
We need to set up a new server for a developer to use. 

He needs to be able to connect with ssh from server1 to server2 as the dev user, without having to enter a password password.

# Objetivos

* Enable SSH to Connect Without a Password from the `dev` User on `server1` to the `dev` User on `server2`
* Copy All tar Files from `/home/dev/` on `server1` to `/home/dev/` on `server2`, Extract Them, and Redirect Output to `/home/dev/tar-output.log`
* Set the Umask So That New Files Are Only Readable and Writeable by the Owner
* Verify the `/home/dev/deploy.sh` Script Is Executable and Run It