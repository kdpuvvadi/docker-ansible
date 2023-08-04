# Docker Ansible Playbook


## Setup

1. Install pip `sudo apt install python3-pip -y`
2. install ansible with pip `pip install ansible`
3. Install docker sdk for ansible `pip install docker`
4. Install requirements `ansible-galaxy collection install -r requirements.yml`

## Run

1. Clone the repo.
2. copy `inventory.ini.j2` to `inventory.ini`.
3. Change host ip of the host.

## Run the playbook

Run `ansible-playbook main.yml`
