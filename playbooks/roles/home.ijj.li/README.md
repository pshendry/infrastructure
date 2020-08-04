# `home.ijj.li` Role

Tasks specific to the `home.ijj.li` host.

Tags:

- `provision`: Provisions the host
- `deploy`: Deploys services
- `update`: Applies updates to the services
- `upgrade`: Applies updates to the system and to services
- `withdraw`: Un-deploys services

## Notes

- Accessing the `nextcloud-mariadb` database:
  - `podman exec -it nextcloud-mariadb mysql -uroot -p`