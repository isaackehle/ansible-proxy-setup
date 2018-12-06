# Ansible Role - proxy-setup

Configure a system to use a Proxy Server

Available on Ansible Galaxy: [pgkehle.proxy-setup](https://galaxy.ansible.com/pgkehle/proxy-setup)


# Examples

```YAML

  - hosts: all
  
    vars:
      proxy:
        addr:   my.fqdn
        port:   3128
  
    roles:
      - pgkehle.proxy-setup
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

### References

* http://digitaldrummerj.me/proxy-configurations/
* http://askubuntu.com/questions/664777/systemwide-proxy-settings-in-ubuntu
* http://www.linuxsecrets.com/blog/6managing-linux-systems/2015/05/26/1490-manually-change-ubuntu-proxy-settings-from-cli-command-line-terminal
