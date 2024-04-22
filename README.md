<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia de Instalação Agentes Portainer 🚀</p>
</p>
  
<p align="center">
<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
<span>Grupo WhatsaAPP: </span>
<a href="https://link.cwmkt.com.br/quepasa" target="_blank">Grupo</a>
</p>

<hr />
<hr />

### PASSO 01: Servidor principal Portainer
  
Acesse painel portainer ( Principal Portainer )

Nevegue até Environments > add environment

![image](https://github.com/cwmkt/serverportainer/assets/91642837/6cfe2632-96d9-4e07-94ac-6064fdd1f314)

Docker Swarm > Start Wizard

![image](https://github.com/cwmkt/serverportainer/assets/91642837/321cf61a-63b9-4beb-abcf-1d6f8a83ae59)


Agente

![image](https://github.com/cwmkt/serverportainer/assets/91642837/87e08495-d553-4e69-9f4c-97cd574f0a59)

Copio codigo na aba (Linux & Windows WSL) para colar na segunda maquina

Conectar segunda maquina 

## PASSO 01: Servidor principal Portainer
Necessario ter docker instalado na segunda máquina 

```bash
apt install docker.io
```

```bash
docker swarm init
```

Execute codigo gerado na opção anterior

Linux & Windows WSL

Volte ao `SERVIDOR_PRINCIPAL` e coloque as informações 

Name: SegundoServer ( Nome Server )<br>
Environment address: ip:9001 ( IP do servidor seguido 9001 )

![image](https://github.com/cwmkt/serverportainer/assets/91642837/52f0a29b-2692-41a0-a35a-257e28cee947)
