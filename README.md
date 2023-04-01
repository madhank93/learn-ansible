# learn-ansible

## Q&A

<details>

  <summary> 1. How does SSH connectivity works ? </summary>

  <p>

![ssh_connectivity](img/ssh_connectivity.png)

![ssh_key_auth](img/ssh_key_auth.png)

The `known_hosts` file lets the client authenticate the server, to check that it isn't connecting to an impersonator. The `authorized_keys` file lets the server authenticate the user.

### Reference

- https://security.stackexchange.com/questions/20706/what-is-the-difference-between-authorized-keys-and-known-hosts-file-for-ssh
- https://www.ssh.com/academy/ssh/public-key-authentication
- https://cryptography.io/en/latest/hazmat/primitives/asymmetric/index.html#asymmetric-algorithms

  </p>

</details>

---

<details>

  <summary> 2. Location of Ansible Configuration Settings ? </summary>

  <p>

Changes can be made and used in a configuration file which will be searched for in the following order:

- `ANSIBLE_CONFIG` - environment variable if set (Highest priority)
- `ansible.cfg` - in the current directory
- `~/.ansible.cfg` - in the home directory
- `/etc/ansible/ansible.cfg` (Lowest priority)

Reference:

- https://docs.ansible.com/ansible/latest/reference_appendices/config.html#ansible-configuration-settings

</p>

</details>

---

<details>

  <summary>  </summary>

  <p>

  </p>

</details>

---

<details>

  <summary>  </summary>

  <p>

  </p>

</details>

---

<details>

  <summary>  </summary>

  <p>

  </p>

</details>

---

<details>

  <summary>  </summary>

  <p>

  </p>

</details>

---

<details>

  <summary>  </summary>

  <p>

  </p>

</details>

---

### Resources

- [Dive Into Ansible - Beginner to Expert in Ansible - DevOps](https://www.udemy.com/course/diveintoansible/)
