# create-ssh

This script is intended to be able to generate a ssh key on windows, mac and linux and then automatically copy the public key for use in github or bitbucket for multi-ssh configuration.

## Prerequisites (Windows)

On Windows you must have one of the following installed

- bash
- cygwin

## How to use

- Clone the repo
- Add the file to your path variable (Optional)


```windows
sh create-ssh
```

Finally login via ssh:

```
ssh -T git@github.com

ssh -T git@bitbucket.org
```

If you added a suffix login via:

```
ssh -T git@github-<suffix>.com

ssh -T git@bitbucket-<suffix>.org
```
