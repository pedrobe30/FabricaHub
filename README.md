# 🎓 FabricaHub | Sistema de Gestão Acadêmica

> **Status do Projeto:** 🚧 Em Concepção (Fase de Gerência de Produto e UX/UI)


O **FabricaHub** é uma plataforma moderna de gestão acadêmica criada para eliminar os pontos de atrito entre o corpo docente e discente. Nascido da necessidade de substituir planilhas desorganizadas e processos dependentes de internet instável, o sistema centraliza chamadas, notas e o plano de ensino em uma interface fluida, offline-first e centrada no usuário.

---

## 🎯 O Problema e a Solução

Muitas instituições sofrem com a "dor da infraestrutura". Professores gastam um tempo valioso tentando registrar presenças e notas em sistemas complexos ou planilhas de Excel que não carregam devido à oscilação da internet. Por outro lado, os alunos sofrem com a ansiedade e a falta de transparência sobre seu desempenho.

**A Solução:** Um sistema mobile-first que permite o registro em cache (offline) para os professores e um dashboard preditivo e transparente para os alunos.

---

## 🧠 Gerência de Produto (Product Management)

Acreditamos que um bom código nasce de um excelente planejamento. Atualmente, nosso foco está na estruturação sólida do produto antes do desenvolvimento técnico. Nossa esteira de PM inclui:

* **Mapeamento de Personas e Mapa de Empatia:** Compreensão profunda das dores do Professor (ex: Lázaro) e do Aluno (ex: Lucas).
* **Priorização MoSCoW:** Definição clara do que é vital para o nosso MVP (Minimum Viable Product), garantindo entregas rápidas e de alto valor.
* **Jornada do Usuário (User Journey):** Mapeamento de todos os pontos de atrito (Pain Points) atuais para desenhar a melhor experiência possível.

---

## 🔄 Fluxos de Processos e Arquitetura

Nossos fluxos estão sendo desenhados para garantir que cada clique tenha um propósito. Estamos documentando:

1.  **Fluxo de Chamada Offline:** Como o sistema lida com a falta de internet, salva os dados em cache e sincroniza com o banco de dados assim que a conexão é restabelecida.
2.  **Fluxo de Lançamento e Visibilidade de Notas:** Regras de negócio rígidas para garantir que o Aluno A não tenha acesso aos dados do Aluno B, mantendo total privacidade.
3.  **Cálculos e Regras de Negócio:** Documentação clara das fórmulas de aprovação e limites de faltas.


## 🧠 Gerência de Produto e Empatia 

[cite_start]O sistema não nasce como um mero projeto técnico, mas focado na realidade e nas dores dos seus usuários principais[cite: 416, 512]:


## ⚙️ Escopo do MVP (Minimum Viable Product)

Nossa esteira de desenvolvimento segue a priorização MoSCoW. [cite_start]Para o MVP (Must-Have), garantimos as seguintes funcionalidades[cite: 362, 363, 364]:

* [cite_start]Autenticação de usuários com controle de acesso por perfil (Aluno, Professor, Coordenador, Admin)[cite: 48, 51, 365, 366].
* [cite_start]Registro de frequência individual e consulta de faltas pelo aluno[cite: 367, 368].
* [cite_start]Lançamento de notas individuais e consulta de notas/médias[cite: 369, 370].
* [cite_start]Cadastramento e listagem de turmas[cite: 371, 372].
* [cite_start]Importação de dados legados do Excel para transição suave[cite: 24, 374].
* [cite_start]Dashboards personalizados para alunos e professores[cite: 376, 377].

**Regras de Negócio Críticas Aplicadas:**
* [cite_start]Frequência mínima obrigatória configurada em 75%[cite: 70].
* [cite_start]Nota mínima para aprovação estabelecida em 6.0[cite: 110].
* [cite_start]Conformidade total com a LGPD para proteção de dados sensíveis de menores[cite: 33, 334].

---

## 🚀 Roadmap e Métricas de Sucesso

O planejamento de entregas foi estruturado para gerar valor no menor tempo possível:

* [cite_start]**Fase 1 (MVP - 5 a 8 semanas):** Entrega funcional do sistema focada nos requisitos essenciais[cite: 506, 507].
* [cite_start]**Fase 2 (Expansão - 3 a 5 meses):** Institucionalização do uso, adição de relatórios e consolidação de dados[cite: 509, 510].

**Como medimos o sucesso?**
* [cite_start]50% dos alunos acessando o painel ao menos 1 vez por semana[cite: 495].
* [cite_start]Redução perceptível de dúvidas em sala sobre frequência e notas[cite: 496].
* [cite_start]Adoção recorrente da plataforma no dia a dia pelos professores[cite: 499].

Desenvolvido com ☕ e foco no usuário por [Pedro Bernardo].
