# Repositório de Estudos - DevOps

Este repositório foi criado para registrar meu aprendizado sobre **DevOps** e **Nuvem (Google Cloud, Azure, AWS)** durante o curso do Iago Ferreira e outros documentos que estudo sobre DevOps. Ele inclui anotações, exemplos de códigos, links úteis, erros que aconteceram e meu aprendizado como um todo.

## Estrutura do Repositório

- **Modulo1_Vagrant**: Aprendizado sobre Vagrant e primeiros passos.
- **Modulo1.A_Projetos_Vagrant**: Projetos que eu criei de acordo com o curso e os desafios, incluindo comandos importantes.
- **Outros Módulos**: Serão adicionados conforme avanço nos cursos.

## Links Úteis

- [Documentação Oficial do Vagrant](https://www.vagrantup.com/docs)
- [Guia sobre Provisionamento com Shell](https://www.shellscript.sh/)
- [Configuração de Redes com Vagrant](https://www.vagrantup.com/docs/networking)

## Como Usar Este Repositório

1. Navegue até o módulo desejado.
2. Consulte o arquivo `README.md` dentro da pasta do módulo para entender os exemplos e instruções.
3. Teste os códigos em seu ambiente local.

---

### Módulo 1: Vagrant

**Objetivo:** Aprender os conceitos básicos e avançados de Vagrant, incluindo provisionamento e redes.

#### Passos Realizados

1. Instalação do Vagrant no Windows e Linux.
2. Pesquisa e download de boxes.
3. Configuração inicial de um `Vagrantfile`.
4. Configuração de redes com Forwarded Ports e Public Networks.

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

**Mais módulos serão documentados aqui à medida que avanço nos estudos.**
