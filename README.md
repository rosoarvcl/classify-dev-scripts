# Getting started

```
cd ~/Projects/ClassifyLearning
git clone git@github.com:rosoarvcl/cl-scripts.git
```

## Local
To save your custom script globally and make it accessible from anywhere on your system

- Make the script executable

    `chmod +x ~/path/to/your/classify_php.sh`

- Place custom script in a directory that is already in the system's PATH (/usr/local/bin). Use symlink

    `sudo ln -s ~/path/to/your/classify_php.sh /usr/local/bin/classify_php`

- Test the command

    `classify_php`

## Adding scripts for Docker PHP container

- Create the script
- Make the script executable

    `chmod +x ~/path/to/your/classify_update`

- Place custom script in a directory that is already in the system's PATH (/usr/local/bin). Use symlink

    `sudo ln ~/path/to/your/classify_update ~/Projects/ClassifyLearning/docker/html`

- Test the command

```
classify_php
bash classify_update
```