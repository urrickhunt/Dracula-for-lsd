### [LSD](https://github.com/lsd-rs/lsd)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash

    git clone https://github.com/dracula/lsd.git

```

#### Install manually

- Download using the [dracula.zip](https://github.com/dracula/lsd/files/11355419/dracula.zip) link or
- Download using the [GitHub `.zip` download](https://github.com/dracula/lsd/archive/refs/heads/main.zip) option and unzip them.

#### Activating theme

#### Mac or Linux

1. Create a theme folder in lsd ~/.config/lsd/themes/.yaml
2. Place [dracula.zip](https://github.com/dracula/lsd/files/11355419/dracula.zip) in the theme folder
2. In the config.yaml change the line to

        theme: dracula
3. If there is no config file please feel free to use this one [config.zip](https://github.com/dracula/lsd/files/11355414/config.zip)        

#### Windows

1.  On Windows systems lsd only looks for the config.yaml files in one location: %APPDATA%\lsd
2.  Create a theme folder in lsd, usually in AppData\Roaming\lsd on ARM it will be in AppData\Local\lsd
3.  Place [dracula.zip](https://github.com/dracula/lsd/files/11355419/dracula.zip) in the theme folder
4.  In the config.yaml change the line to

        theme: dracula
5. If there is no config file please feel free to use this one [config.zip](https://github.com/dracula/lsd/files/11355414/config.zip) 


##### Updated Universal Method for lsd 1.0.0+

1. Delete theme folder in `~/.config/lsd`
2. Place both the colors.yaml & config.yaml from the [Updated Colors Method.zip](https://github.com/dracula/lsd/blob/96dfccbadaa8b53b4a013813c04508c9da639ca8/Updated%20Colors%20Method.zip) into `~/.config/lsd` folder