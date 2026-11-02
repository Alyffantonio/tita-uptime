# tita-uptime

Monitor de https://titaaraujo.com.br. A cada 5 minutos o GitHub Actions abre o site e a API.

- Caiu (3 tentativas seguidas falhando): abre uma issue "fora do ar" com o horário e a execução fica vermelha. As duas coisas mandam e-mail para o dono do repositório.
- Voltou: comenta o horário na issue e fecha.
- `historico.md` guarda todas as quedas e voltas.

Para testar na hora: aba Actions, "monitor", Run workflow.
