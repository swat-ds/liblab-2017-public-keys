## LibLab Fellows Week 4: The Cloud is Real

![image of an amazon data center stolen from theatlantic.com](https://cdn.theatlantic.com/assets/media/img/mt/2016/01/08_image/lead_960.jpg?1452270370)

A temporary repository for adding your public keys.

1) [First generate a private/public key pair](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
2) In this repository, click the `Create New File` button
3) Open your public key (`*.pub`) in Atom/Sublime
4) Copy/Paste into GitHub and commit

once you've been added you can go ahead and login:

`ssh -i [path to private key] [user]@34.237.205.134`

You'll also want to copy your p5.js sketch to your home folder on the server:

`scp -i [path to private key] [path to p5.js sketch] [user]@34.237.205.134:~/`
