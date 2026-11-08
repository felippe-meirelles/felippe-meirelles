# Felippe — automação e software para operação técnica

Desenvolvo ferramentas que tiram trabalho manual de operações técnicas: catálogos de produto,
consultas em campo sem internet, automação de rotina diária e integração com equipamento de bancada.

Trabalho de ponta a ponta: base de dados, back-end na borda, interface, script de instalação e
verificação automática do que foi publicado.

---

## O que já construí

### Catálogo técnico automatizado

**Problema:** catálogo de produtos e aplicações técnicas mantido à mão, publicado por planilha,
com risco constante de versão desatualizada no ar.

**O que fiz:** pipeline que lê a base, gera o site estático e publica sozinho todos os dias de manhã.
Inclui conferência de integridade antes de subir, versão anterior mantida para voltar atrás em um
comando e registro do que mudou.

**Resultado:** publicação diária sem intervenção humana, com rollback pronto.

**Tecnologias:** PowerShell, Node, Cloudflare Workers, D1, R2, build estático.

### Consulta em campo (PWA offline)

**Problema:** técnico em campo, sem sinal, precisando consultar aplicação de produto e registrar
atendimento na hora.

**O que fiz:** aplicativo web instalável, com cache offline, busca por código e leitura de etiqueta
pela câmera. Sincroniza quando volta a conexão.

**Tecnologias:** JavaScript, Service Worker, APIs de câmera, Cloudflare Workers, D1.

### Software de bancada de teste

**Problema:** teste de injetores common rail feito em bancada, com resultado anotado à mão e
laudo montado depois.

**O que fiz:** programa desktop que conversa com o equipamento, executa a sequência de teste,
valida o resultado e gera o laudo. Tem simulador para desenvolvimento sem a bancada e instalação
empacotada para as máquinas de oficina.

**Tecnologias:** Python, serial/porta de comunicação, empacotamento em instalador, testes
automatizados de regressão.

---

## Stack

| Área | Ferramentas |
|---|---|
| Automação | PowerShell 5.1, Node, agendador do Windows |
| Nuvem | Cloudflare Workers, D1, R2, KV |
| Front-end | JavaScript, PWA, HTML/CSS |
| Desktop | Python, empacotamento em instalador |
| Prática | Git, versionamento semântico, testes de regressão, rollback |

## Contato

- GitHub: [@felippems-debug](https://github.com/felippems-debug)
- Aberto a conversar sobre automação, integração com equipamento e sistemas web.
