+++
title = 'SDumont2nd'
date = 2026-02-06T18:28:09-03:00
draft = true
tags = ["computation", "cluster"]
categories = ["notes"]
+++

# Cheatsheet do SantosDumont2nd 

## Conexão

1. Connect to VPN
		
```bash
#Conectar
sudo vpnc /etc/vpnc/sdumont.conf --enable-weak-encryption


# Desconectar
sudo vpnc-disconnect
```

		
2. Connect to a login node through SSH

```bash
#Conectar
sudo ssh user@login.sdumont.lncc.br

#Ou
sudo ssh user@login.sdumont2nd.lncc.br



# Desconectar
logout
```

## Guia de módulos


```bash
#List available modules
module av
module avail

#List modules
module list

#Load modules
module load openmpi/4.1.3

#Unload module
module purge

#Add path
module use
```

Como adicionar um módulo ao meu ambiente?


```bash
 module load NOME-DO-MODULO
```


