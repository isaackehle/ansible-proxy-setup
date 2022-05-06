# Ansible Role - proxy-setup

Configure a system to use a Proxy Server

Available on Ansible Galaxy: [isaackehle.proxy-setup](https://galaxy.ansible.com/isaackehle/proxy-setup)

## Examples

```YAML

  - hosts: all
    vars:
      proxy:
        addr: my.fqdn
        port: 3128

    roles:
      - isaackehle.proxy-setup
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))

### References

- [From Digital Drummer](http://digitaldrummerj.me/proxy-configurations/)
- [From Ask Ubuntu](http://askubuntu.com/questions/664777/systemwide-proxy-settings-in-ubuntu)
- [From Linux Secrets](http://www.linuxsecrets.com/blog/6managing-linux-systems/2015/05/26/1490-manually-change-ubuntu-proxy-settings-from-cli-command-line-terminal)
