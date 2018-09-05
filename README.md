# pixelbook-config

Stolen and modified ansible bootstrap of my personal chromebook, cb3-431


* Installs Atom
* Installs zeal (a documentation viewer)
* Installs rclone (for potentially syncing data from the linux container to a gdrive folder)
* Installs some standard linux packages (man and potentially others)
* Configures and installs powerline-shell with a corresponding .bash_profile

## Installation

1. Clone this repository.
2. Run `./bootstrap.sh` to install ansible and a basic ansible inventory file.
3. Uncomment and update the variables in `config-options.yaml` to taste.
4. Run `ansible-playbook pixelbook.yml` to install standard applications and configuration.
