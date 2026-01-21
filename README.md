# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21/01/2026  
Empresa: Farmácia Virtual Cloud (empresa fictícia)  
Responsável: Lucas Costa

---

## Introdução

Este relatório apresenta o processo de implementação de serviços na Amazon Web Services (AWS) para a construção de uma plataforma virtual de uma farmácia fictícia. O projeto foi desenvolvido com o objetivo de aplicar conceitos de computação em nuvem em um cenário próximo ao real, abordando aspectos como segurança, disponibilidade, escalabilidade e organização da infraestrutura, além de proporcionar aprendizado prático sobre os principais serviços da AWS.

---

## Descrição do Projeto

O projeto de implementação da infraestrutura em nuvem foi dividido em 3 etapas, cada uma com objetivos específicos. A seguir, são descritas as etapas do projeto:

### Etapa 1:
- **Nome da ferramenta:** Amazon VPC  
- **Foco da ferramenta:** Isolamento e organização da rede  
- **Descrição do caso de uso:**  
  Foi criada uma Amazon Virtual Private Cloud (VPC) para segmentar e isolar a rede da aplicação da farmácia virtual. Dentro da VPC foram configuradas sub-redes públicas e privadas, permitindo a separação entre recursos acessíveis pela internet e recursos internos, garantindo maior segurança e controle do tráfego de rede.

### Etapa 2:
- **Nome da ferramenta:** Amazon EC2  
- **Foco da ferramenta:** Processamento e hospedagem da aplicação  
- **Descrição do caso de uso:**  
  As instâncias Amazon EC2 foram utilizadas para hospedar a aplicação web da farmácia virtual. As instâncias foram posicionadas em sub-redes públicas, permitindo o acesso externo por usuários finais. Regras de segurança foram aplicadas por meio de Security Groups, controlando o tráfego de entrada e saída das instâncias.

### Etapa 3:
- **Nome da ferramenta:** Amazon RDS  
- **Foco da ferramenta:** Armazenamento e gerenciamento de dados  
- **Descrição do caso de uso:**  
  O Amazon RDS foi utilizado para hospedar o banco de dados da aplicação, armazenando informações relacionadas a produtos, usuários e pedidos. O banco de dados foi configurado em uma sub-rede privada, garantindo maior segurança, alta disponibilidade e gerenciamento automatizado de backups e manutenção.

---

## Conclusão

A implementação dos serviços AWS na plataforma da farmácia virtual atingiu os objetivos propostos, proporcionando uma infraestrutura organizada, segura e escalável. A utilização da Amazon VPC, EC2 e RDS permitiu simular um ambiente real de produção em nuvem, aumentando a confiabilidade da solução e contribuindo para o aprendizado prático sobre computação em nuvem. Recomenda-se a continuidade da utilização da infraestrutura implementada e a evolução do projeto com a adoção de novos serviços AWS, como Load Balancer e Auto Scaling.

---

## Anexos

- Diagrama da arquitetura da solução  
- Prints da configuração da VPC e sub-redes  
- Prints das instâncias EC2  
- Prints da configuração do banco de dados RDS  

---

Assinatura do Responsável pelo Projeto:


Lucas Costa S.
