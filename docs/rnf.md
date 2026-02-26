## Requisitos Não Funcionais (RNF)

### RNF01 — Tempo de resposta
O sistema deve carregar telas principais em até **2 segundos**.

### RNF02 — Segurança
As senhas devem ser armazenadas usando hash seguro (ex.: bcrypt).

### RNF03 — Compatibilidade
O sistema deve funcionar nos navegadores Chrome, Edge e Firefox.

### RNF04 — Disponibilidade
O sistema deve garantir um uptime (tempo de atividade) de 99,9%, estando disponível 24/7.

### RNF05 — Responsividade
A interface deve ser adaptável para diferentes tamanhos de tela, incluindo desktops, tablets e smartphones.

### RNF06 — Escalabilidade
O sistema deve ser capaz de suportar um aumento de até 50% no volume de acessos simultâneos sem degradação de performance.

### RNF07 — Backup e Recuperação
Devem ser realizados backups automáticos diários de todos os dados do banco, com retenção mínima de 30 dias.

### RNF08 — Protocolo de Comunicação
Toda a comunicação entre o cliente e o servidor deve ser realizada através do protocolo HTTPS com certificado SSL válido.

### RNF09 — Usabilidade
O sistema deve seguir as heurísticas de Nielsen, garantindo que um novo usuário consiga realizar tarefas básicas sem treinamento prévio.

### RNF10 — Conformidade Legal (LGPD)
O armazenamento e tratamento de dados pessoais devem seguir rigorosamente a Lei Geral de Proteção de Dados (LGPD).
