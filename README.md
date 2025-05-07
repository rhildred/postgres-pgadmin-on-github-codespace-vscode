# LCBO database

Postgres database with pgadmin4

TLDR;

```bash
ansible-playbook up.yaml
```

To drop the database and take down

```bash
ansible-playbook down.yaml
```

This was based on a [previous codespace](https://github.com/rhildred/monitoring-tracing) that installed everything in the same codespace. The point of this exercise was to give each container 1 responsibility and to use the images from docker hub.