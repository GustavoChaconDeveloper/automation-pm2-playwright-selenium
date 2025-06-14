# 🧠 Automações com Playwright, Selenium e PM2

Neste projeto desenvolvi automações utilizando as bibliotecas **Playwright** e **Selenium**, focadas em interações web automatizadas e coleta de dados. Para garantir que os scripts estejam sempre em execução, mesmo após falhas ou reinicializações, utilizei o **PM2**, um poderoso gerenciador de processos para Node.js e scripts diversos.

---

## 🚀 Sobre o PM2

**PM2** é um process manager avançado que permite:

- Executar e monitorar múltiplos scripts em segundo plano;
- Reiniciar processos automaticamente em caso de falhas;
- Registrar logs detalhados;
- Visualizar consumo de CPU e memória;
- Manter os processos ativos mesmo após reinicializações do sistema (via `pm2 startup`).

---

## ⚙️ Aplicação prática

Os scripts foram cadastrados com nomes como:

- `api-simples`
- `list-users`
- `ranking`

Cada processo é monitorado em tempo real e reiniciado automaticamente em caso de parada inesperada. Isso garante alta disponibilidade das automações, além de facilitar o diagnóstico de falhas com logs e métricas.

### 🖥️ Exemplo de execução com PM2

![Execução com PM2]([https://img001.prntscr.com/file/img001/MrV2e4Q1R-K4_cbVuq_MnA.png])

---

## 💡 Benefícios

- Nenhuma automação é interrompida por falhas pontuais;
- Uso de memória e CPU monitorado constantemente;
- Logs armazenados para análise posterior;
- Pode ser usado também em servidores para manter bots ou tarefas agendadas 24/7.

---

