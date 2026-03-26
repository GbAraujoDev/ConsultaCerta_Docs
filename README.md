# 🏥 Projeto Eixo - Consulta Certa

> **Sistema inteligente de agendamento e histórico médico focado em acessibilidade para idosos e inclusão digital.**

---

## 📝 Sobre o Projeto
O **Consulta Certa** nasceu para solucionar a dificuldade de acesso a serviços de saúde por pessoas com baixa familiaridade tecnológica. O sistema centraliza agendamentos, documentos e históricos médicos em uma interface simples, intuitiva e segura.

## 🎯 Objetivos
* **Simplificar** o agendamento de consultas e exames.
* **Centralizar** o histórico clínico (laudos, receitas e faltas).
* **Notificar** usuários em tempo real para reduzir o absenteísmo.
* **Garantir** a segurança dos dados sensíveis conforme a **LGPD**.

---

## 📋 Especificação de Requisitos Funcionais (RF)

| ID | Descrição do Requisito | Eu como... | Quero/Desejo/Preciso | Para... | Responsável | Página |
|:---:|:---|:---:|:---|:---|:---:|:---:|
| **RF-01** | Permitir o cadastro de usuários | Paciente | Realizar meu cadastro (CRUD) (incluir, consultar/pesquisar, alterar, deletar) | Ter acessos às funcionalidades do sistema e gerenciar minhas informações pessoais | Lorena | Cadastro |
| **RF-02** | Permitir cadastro de profissional de saúde. | Profissional de saúde|Realizar meu cadastro – (CRUD) (incluir, consultar/pesquisar, alterar, deletar)| Divulgar meu trabalho, captar clientes e aumentar renda. | Lorena | Cadastro |
| **RF-03** |Exibir a agenda de consultas e exames do paciente| Paciente ou Profissional de saúde| Visualizar os dados de consultas e possíveis exames dos pacientes.|Se manter informado e se planejar para os próximos encontros com os médicos. |  | Inicial |
| **RF-04** |Informar o tipo de atendimento, data, horário, local e unidade responsável| Paciente | Visualizar informações mais específicas sobre as consultas como horário, tipo do atendimento e local.|Se manter informado e se planejar para os próximos encontros com os médicos | Emily | |
| **RF-05** |Enviar notificações com lembretes sobre consultas e exames agendados| Paciente| Ser lembrado acerca dos compromissos hospitalares sem necessariamente precisar abrir o aplicativo.|Diminuir as chances de esquecimentos dos dados das consultas e exames| Gabriel | Configurações/Api |
| **RF-06** |Exibir orientações sobre documentos necessários e preparo para exames.| Paciente| Visualizar as orientações.| Se antecipar para o caso de jejuns necessários para exames e para providenciar documentos.| | |
| **RF-07** |Permitir a confirmação de presença no atendimento.| Paciente |Confirmar minha presença a consulta.| Atualizar o status do agendamento e evitar marcação indevida de falta (absenteísmo). | Emily | Config |
| **RF-08** | Permitir o informe de cancelamento. | Paciente | Cancelar minha presença a consulta. | Informar sobre o meu não comparecimento na consulta sem precisar ir até a instituição fisicamente.| | |
| **RF-09** | Armazenar o histórico de atendimentos, consultas, exames e faltas.| Paciente ou Profissional |Acessar registros de eventos médicos e administrativos passados. |Ter uma visão completa da jornada do paciente e auxiliar na tomada de decisão clínica.| Gabriel |Prontuário / Histórico|
| **RF-10** | O sistema deve disponibilizar um painel administrativo com relatórios de agendamentos, confirmações, cancelamentos e faltas. | Profissional de saúde |Visualizar os  dados de cada paciente  pertinentes a mim.|Ter uma base dados para me | ||
| **RF-11** | O sistema deve ter um tamanho de fonte ajustável. | Paciente |Facilitar a visualização das informações | Facilitar a visualização das informações.| |Todas|
| **RF-12** |O sistema deve permitir o envio de documentos digitais relacionados ao atendimento. | Paciente ou Profissional|Realizar o upload de exames, receitas e laudos (PDF/Imagens).|Centralizar o histórico médico e facilitar a consulta durante o atendimento.| | |
| **RF-13** | O sistema deve permitir notificações em tempo real sobre alterações nos agendamentos.| Paciente ou Profissional| Receber alertas imediatos sobre confirmações, cancelamentos ou atrasos.|Evitar desencontros e manter a agenda sempre atualizada para ambas as partes.| | |
| **RF-14** |O sistema deve permitir integração futura com sistemas do SUS. | Administrador |Estruturar os dados conforme padrões de interoperabilidade de saúde. |Garantir que os dados possam ser partilhados com a rede pública no futuro.| ||
---

## ⚙️ Requisitos Não Funcionais (RNF)

| ID | Descrição | Prioridade |
|:---:|:---|:---:|
| **RNF-01**|O sistema deve apresentar uma interface clara, com organização lógica das informações, uso de ícones compreensíveis, botões bem identificados e navegação simples, permitindo que qualquer usuário, mesmo com pouca experiência tecnológica, consiga utilizar o sistema sem dificuldade. | **ALTA** |
| **RNF-02**| O sistema deve ser totalmente responsivo, adaptando automaticamente sua interface para diferentes dispositivos e tamanhos de tela, incluindo smartphones, tablets e computadores, sem perda de funcionalidade ou legibilidade. | **Médio** |
| **RNF-03**| O sistema deve utilizar linguagem simples, direta e de fácil compreensão, evitando termos técnicos complexos, para garantir que usuários de diferentes níveis de escolaridade consigam entender todas as informações e instruções apresentadas.| **Médio** |
| **RNF-04**| O sistema deve garantir acessibilidade visual, incluindo:<br>• uso de cores com alto contraste;<br>• fontes legíveis e de tamanho adequado;<br>• suporte a leitores de tela;<br>• opção de modo claro e modo escuro para melhor adaptação à iluminação do ambiente e conforto do usuário.| **ALTA** |
| **RNF-05**| O sistema deve garantir a proteção dos dados dos usuários por meio de autenticação segura, controle de acesso por perfis (paciente, familiar, administrador e unidade de saúde) e uso de protocolos de criptografia (HTTPS), assegurando a privacidade e integridade das informações. | **ALTA** |

---

## 👥 Equipe do Projeto
* **Cláudio Gabriel Araújo Chaves** 
* **Franklin Inácio Santos Guimarães** 
* **Kauan de Sousa Vilaça** 
* **Lorena Ferreira Fernandes**
* **Lucas de Paula Garcia**
* **Luiz Gustavo Fernandes Ribeiro**
* **Emily Alves Costa**
---
*Documentação gerada para a disciplina de Projeto Eixo - 2026*
