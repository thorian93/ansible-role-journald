# Ansible Role: Journald

This role ensures persistent logging for journald on RHEL/CentOS, Debian/Ubuntu and Fedora servers.

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like:

    - hosts: foobar
      roles:
        - role: ansible-role-journald
          become: yes

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: foobar
      become: yes
      roles:
        - ansible-role-journald

## Contributing

Please feel free to open issues if you find any bugs, problems or if you see room for improvement. Also feel free to contact me anytime if you want to ask or discuss something.

## Disclaimer

This role is provided AS IS and I can and will not guarantee that the role works as intended, nor can I be accountable for any damage or misconfiguration done by this role. Study the role thoroughly before using it.

## License

GPLv3

## Author Information

This role was created in 2019 by [Thorian93](https://thorian93.de/).
