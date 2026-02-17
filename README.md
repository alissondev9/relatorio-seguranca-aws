# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 17 de fevereiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** [Seu nome]

---

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **[seu nome]**. O objetivo do projeto foi elencar 3 medidas de segurança em serviços da AWS, com a finalidade de aumentar a proteção dos dados, controlar acessos e reduzir riscos operacionais.

---

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas da implementação:

---

### Etapa 1
- **Nome da ferramenta:** AWS Identity and Access Management (IAM)  
- **Foco da ferramenta:** Controle de acesso e gerenciamento de permissões  
- **Descrição de caso de uso:**  
Foi implementado o serviço IAM para criação de usuários, grupos e políticas de acesso com o princípio do menor privilégio. Cada colaborador passou a ter permissões apenas para os recursos necessários ao seu trabalho, reduzindo riscos de acessos indevidos ou alterações acidentais na infraestrutura.

**Benefício principal:** Maior controle de acessos e redução de riscos de segurança.

---

### Etapa 2
- **Nome da ferramenta:** AWS Shield + AWS Web Application Firewall (WAF)  
- **Foco da ferramenta:** Proteção contra ataques e tráfego malicioso  
- **Descrição de caso de uso:**  
Foi configurado o AWS Shield para proteção contra ataques DDoS e o AWS WAF para filtrar requisições maliciosas em aplicações web. Foram criadas regras para bloquear IPs suspeitos, limitar requisições e proteger contra ataques comuns, como SQL Injection e Cross-Site Scripting (XSS).

**Benefício principal:** Proteção contra ataques externos e maior disponibilidade das aplicações.

---

### Etapa 3
- **Nome da ferramenta:** AWS CloudTrail  
- **Foco da ferramenta:** Monitoramento e auditoria de atividades  
- **Descrição de caso de uso:**  
Foi implementado o AWS CloudTrail para registrar todas as ações realizadas na conta AWS, incluindo acessos, alterações de configurações e uso de serviços. Esses registros permitem auditorias, identificação de atividades suspeitas e rápida resposta a incidentes de segurança.

**Benefício principal:** Rastreabilidade das ações e melhoria na resposta a incidentes.

---

## Conclusão
A implementação das medidas de segurança na empresa **Abstergo Industries** tem como resultado esperado o aumento da proteção dos dados, melhor controle de acessos, redução de riscos de ataques e maior confiabilidade da infraestrutura em nuvem, o que aumentará a eficiência e a produtividade da empresa.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a adoção de novas práticas de segurança, como autenticação multifator (MFA), criptografia de dados e monitoramento contínuo de ameaças.

---

## Anexos
- Políticas de acesso configuradas no IAM  
- Regras aplicadas no AWS WAF  
- Relatórios de auditoria do AWS CloudTrail  

---

**Assinatura do Responsável pelo Projeto:**  
[Seu nome]
