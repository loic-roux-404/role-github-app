# Github app

Semi automation of github app creation

- Launch a server [locahost:2000](http://locahost:2000) to create an app from a [app manifest](https://docs.github.com/en/developers/apps/building-github-apps/creating-a-github-app-from-a-manifest)

## Install to requirements.yml

```
- src: git+git@github.com:loic-roux-404/role-github-app
  version: master
```

## Requirements

None

## Role Variables

- Check [defaults.yml](./defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: role-github-app }
```

## License

MIT

## Author Information

[Loic Roux](github.com/loic-roux-404)
