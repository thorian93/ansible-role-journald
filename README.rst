# Ansible Role: Journald

Ensures persistent logging for journald on RHEL/CentOS, Debian/Ubuntu and Fedora servers.

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like:

    - hosts: foobar
      roles:
        - role: ansible-journald
          become: yes

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: foobar
      become: yes
      roles:
        - ansible-journald

## License

GPLv3

## Author Information

This role was created in 2019 by [Thorian93](https://thorian93.de/).
