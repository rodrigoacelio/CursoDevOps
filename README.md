# Repositório de Estudos - Vagrant

Este repositório foi criado para registrar meu aprendizado sobre **Vagrant** e **Provisionamento** durante o curso do Iago Ferreira. Ele inclui anotações, exemplos de códigos e links úteis para consulta futura.

## Estrutura do Repositório

- **Modulo1_Instalacao**: Aprendizado sobre instalação do Vagrant e primeiros passos.
- **Modulo2_Provisionamento**: Criação de máquinas virtuais e provisionamento usando Shell Scripts.
- **Modulo3_Redes**: Configuração de redes com Vagrant, incluindo Forwarded Ports e Public Networks.
- Outros módulos serão adicionados conforme avanço no curso.

## Links Úteis

- [Documentação Oficial do Vagrant](https://www.vagrantup.com/docs)
- [Guia sobre Provisionamento com Shell](https://www.shellscript.sh/)
- [Configuração de Redes com Vagrant](https://www.vagrantup.com/docs/networking)

## Como Usar Este Repositório

1. Navegue até o módulo desejado.
2. Consulte o arquivo `README.md` dentro da pasta do módulo para entender os exemplos e instruções.
3. Teste os códigos em seu ambiente local.

---

### Módulo 1: Instalação do Vagrant

**Objetivo:** Instalar o Vagrant e configurar o ambiente inicial.

#### Passos Realizados

1. Instalação do Vagrant no Windows e Linux.
2. Pesquisa e download de boxes.
3. Configuração inicial de um `Vagrantfile`.

#### Comandos Importantes

```bash
# Instalar o Vagrant (Linux - Debian/Ubuntu)
sudo apt-get install vagrant

# Inicializar uma box
vagrant init hashicorp/bionic64

# Subir a máquina virtual
vagrant up

# Conectar via SSH
vagrant ssh
```

#### Links Relacionados

- [Download do Vagrant](https://www.vagrantup.com/downloads)
- [Boxes no Vagrant Cloud](https://app.vagrantup.com/boxes/search)

---

**Mais módulos serão documentados aqui à medida que avanço no curso.**
