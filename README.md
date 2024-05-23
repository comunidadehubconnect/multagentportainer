<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia de Instalação Agentes Portainer 🚀</p>
</p>
  
<p align="center"> 
<a href="https://hubconnect.top" target="_blank">👉 Participe da Comunidade HubConnect 👈</a>
</p>

<hr />
<hr />

### Como conectar vários servidores em apenas uma instancia do Portainer

![image](https://github.com/cwmkt/serverportainer/assets/34479816/5c721729-9b9f-46b3-9a36-bde1f25af0cc)


## PASSO 01: Servidor que vai ser instalado o Agente
Necessario ter docker instalado na máquina 

```bash
apt install docker.io
```

```bash
docker swarm init
```

### PASSO 02: Servidor principal Portainer
  
Acesse painel Portainer ( Principal Portainer )

Nevegue até Environments > add environment

![image](https://github.com/cwmkt/serverportainer/assets/91642837/6cfe2632-96d9-4e07-94ac-6064fdd1f314)

Docker Swarm > Start Wizard

![image](https://github.com/cwmkt/serverportainer/assets/91642837/321cf61a-63b9-4beb-abcf-1d6f8a83ae59)


Escolha o tipo de conexão `Agent`

![image](https://github.com/cwmkt/serverportainer/assets/91642837/87e08495-d553-4e69-9f4c-97cd574f0a59)

Copie o código na aba `(Linux & Windows WSL)` para colar na segunda maquina

Execute codigo gerado na opção `(Linux & Windows WSL)` na segunda máquina

Volte ao `SERVIDOR_PRINCIPAL` e insira as informações: 

Name: SegundoServer ( Nome Server )<br>
Environment address: ip:9001 ( IP do servidor seguido 9001 )

![image](https://github.com/cwmkt/serverportainer/assets/91642837/52f0a29b-2692-41a0-a35a-257e28cee947)

**Pronto tudo Funcionando** ✅😎
