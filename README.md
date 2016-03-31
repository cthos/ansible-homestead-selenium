# ansible-homestead-selenium

An Ansible playbook for installing local selenium / Chrome / X on a homestead box.

## Instructions

1. `cd` into this directory after cloning the repository
2. Change the `inventory` file to accurately reflect your local homestead url (it should ssh as vagrant automagically)
3. Run `ansible-playbook selenium_homestead.yml -i inventory`
4. Whenever you want to run selenium just run the `seleniumrun` command.
