# KUMC


**------------------------------------------------------------------------------June_1_2023---------------------------------------------------------------------------------------------**

**sudo apt-get update**:upgrade command downloads and installs the updates for each outdated package and dependency on your system.

**sudo apt-get install xxx**:command is used to download the latest version of your desired application from an online software repository pointed to by your sources.

**tmux**: allows you to create several "pseudo terminals" from a single terminal.

**Ctrl D**: kill the session.

**tmux ls**: list the running sessions.

0: 1 windows (created Sat Aug 27 20:54:58 2022)

**tmux attach -t 0**: attach session

**Ctrl B D**: detach sesssion

At the bottom part of tmux window: [0]: this is the session name. By default, they’re numbered, starting with zero. 0:bash*: the 0 indicates this is the first window in this session.

Reach to server: **ssh tenor.ifx.kumc.edu**

**ssh-keygen**: an SSH key is used to access a remote server through an SSH connection. The keys come in pairs, a public key and a private key. The public key is kept within the server and the private key is with the user or the client.

A public key that is copied to the SSH server(s). 

A private key that remains (only) with the user.

**Setting Up Public Key Authentication for SSH**

The following simple steps are required to set up public key authentication (for SSH):

1.Key pair is created (typically by the user). This is typically done with ssh-keygen.

2.Private key stays with the user (and only there), while the public key is sent to the server. Typically with the ssh-copy-id utility.

3.Server stores the public key (and "marks" it as authorized).

4.Server will now allow access to anyone who can prove they have the corresponding private key.
