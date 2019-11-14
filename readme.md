
## Installation

  1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  2. [Install Ansible](http://docs.ansible.com/intro_installation.html).
  3. Clone this repository to your local drive.
  4. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  5. Run `ansible-playbook main.yml -i inventory -K` inside this directory. Enter your account password when prompted.

sudo xcodebuild -license accept


# Requirements

- HomeBrew
- Git setup and credentials
- Ansible setup
- `ansible-galaxy install -r requirements.yml -p ./roles`

# Run

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook playbook-mac.yml --ask-become-pass
```
