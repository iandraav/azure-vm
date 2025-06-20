# Desafio de Projeto: Criando e Configurando uma Máquina Virtual no Microsoft Azure

Repositório criado para o Desafio de Projeto do bootcamp **Microsoft 50 Anos - Computação em Nuvem com Azure** da [Digital Innovation One](https://www.dio.me/).

## 📌 Índice
- [Visão Geral do Projeto](#-visão-geral-do-projeto)
- [Ferramentas e Tecnologias](#-ferramentas-e-tecnologias)
- [Passo a Passo da Execução](#-passo-a-passo-da-execução)
- [Desafios e Soluções](#-desafios-e-soluções)
- [Conclusão](#-conclusão)
- [Autor](#-autor)

---

## 📖 Visão Geral do Projeto
O objetivo deste projeto foi aplicar os conhecimentos adquiridos sobre os serviços de computação em nuvem da Microsoft Azure, especificamente na criação e configuração de uma Máquina Virtual (VM). O processo envolveu desde o provisionamento do recurso no Portal Azure até a conexão remota e a instalação de um servidor web para validar a funcionalidade da VM.

---

## 🛠️ Ferramentas e Tecnologias
- **Microsoft Azure:** Plataforma de nuvem principal.
- **Máquinas Virtuais (VMs) do Azure:** Serviço de IaaS para criar servidores virtuais.
- **Grupos de Recursos do Azure:** Para organizar os recursos do projeto.
- **Redes Virtuais (VNet) e Grupos de Segurança de Rede (NSG):** Para conectividade e segurança.
- **:** Sistema Operacional da VM.
- **:** Ferramenta para conexão remota.
- **:** Software instalado para validação.
- **Git & GitHub:** Para controle de versão e documentação do projeto.

---

## ⚙️ Passo a Passo da Execução

### 1. Criação do Grupo de Recursos
O primeiro passo foi criar um Grupo de Recursos para agrupar todos os ativos do projeto, facilitando o gerenciamento e a organização.
![Tela de criação do Grupo de Recursos](images/01-grupo-de-recursos.png)

### 2. Provisionamento da Máquina Virtual
Com o Grupo de Recursos pronto, a próxima etapa foi provisionar a Máquina Virtual, configurando seus aspectos essenciais:
- **Configurações Básicas:** Nome, Região, Sistema Operacional e Tamanho (Hardware).
- **Segurança:** Definição de usuário/senha e liberação da porta de acesso remoto (22 para SSH ou 3389 para RDP) no Grupo de Segurança de Rede (NSG).

![Configurações básicas da VM](images/02-criacao-vm-basico.png)

🧠 **Aprendizado Chave:** A configuração do NSG é um ponto crítico de segurança. Compreendi que, por padrão, o acesso é restrito e deve ser liberado explicitamente, o que é uma prática de segurança fundamental na nuvem.

### 3. Conexão Remota à VM
Após o deploy da VM, realizei a conexão remota para começar a interagir com o servidor.

![Terminal conectado via SSH](images/03-conexao-ssh-sucesso.png)

### 4. Instalação e Validação do Servidor Web
Para confirmar que a VM estava funcional e acessível pela internet, instalei um servidor web. .

O acesso ao IP público da VM pelo navegador exibiu a página de boas-vindas, confirmando o sucesso da instalação e da configuração de rede.

![Página de boas-vindas do Nginx/IIS](images/04-validacao-servidor-web.png)

---

## ❗ Desafios e Soluções
Um desafio encontrado foi .

---

## ✅ Conclusão
Este projeto prático foi fundamental para consolidar os conceitos de IaaS (Infraestrutura como Serviço) no Azure. A experiência de criar, configurar e gerenciar uma VM do zero me proporcionou uma compreensão tangível de como os recursos de computação são disponibilizados na nuvem, destacando a agilidade e a flexibilidade da plataforma em comparação com ambientes on-premise.

---

## 👨‍💻 Autor

**[Seu Nome Completo]**

- [LinkedIn](https://www.linkedin.com/in/seu-usuario/)
- [Perfil DIO](https://web.dio.me/users/seu-usuario)
