[Apache Guacamole](https://guacamole.apache.org/) is a clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH.

This repository contains a ready-made sample project to run in Docker using a single command.

> [!IMPORTANT]  
>All passwords are test passwords. In a real project, replace them with your own.

Enter the following command to run
```sh
docker-compose up -d
```

Go to the following address in your browser

```
http://localhost:8080/guacamole/
```

Default User & Pass: 
`guacadmin`
`guacadmin`