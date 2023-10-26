# `Portainer` using `Multipass`
**Manage containers** using a GUI through `Portainer CE` site, deployed inside a VM using `Multipass`. 

## Commands
Run the following comand to define aliases:
```ssh
source ./bin/set-aliases
```

> `mp` for `M`ultipass + `P`ortainer 

```sh
mplaunch        # For creating a new instance with Portainer
mplistip        # For listing the IP address of instance
mpstart         # For starting the instance
mpstop          # For stopping the instance
mpkill          # For killing the instance
mpstatus        # For getting the instance status
```

## Demo
- Launch a new instance
- Check instance status
- Show instance IP address
- Navigate to Portainer site
- Create a new admin user
- Set local Docker environment
- Set public IP address for enviroment
- Deploy a new container
- Navigate to the deployed container
- Stop instance
- Start instance
- Kill stance

<img src="https://github.com/prmiguel/media/blob/main/64ace362-643e-4b31-828b-5868c48293e9.gif" width="700"/>

## References
- [multipass.run](https://multipass.run/)
- [Portainer](https://www.portainer.io/)
