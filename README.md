# StudioFlow

Painel web para gestão de clientes e agenda de estúdios de beleza e barbearias.

> **Status:** protótipo de front-end em HTML, CSS e JavaScript puro. Os dados ficam salvos no navegador (`localStorage`); o backend ainda não foi implementado.

## O que já funciona

| Tela | Situação |
| :-- | :-- |
| **Clientes** | Cadastro, edição e exclusão (nome, telefone, e-mail e observações), com contador e estado vazio |
| **Profissionais** | Cadastro, edição e exclusão (nome, especialidade, telefone, e-mail e observações) |
| **Serviços** | Cadastro, edição e exclusão (nome, descrição, duração e preço) |
| **Agendamentos** | Interface do formulário e da lista, ainda com dados de exemplo |
| **Dashboard** | Interface do painel, ainda com dados de exemplo |

## Como rodar

Não precisa instalar nada: abra `frontend/index.html` no navegador.

Se preferir um servidor local:

```bash
cd frontend
python3 -m http.server 8000
# abra http://localhost:8000
```

## Estrutura

```
frontend/
  index.html · dashboard.html · clientes.html
  profissionais.html · servicos.html · agendamentos.html
  css/style.css
  js/clientes.js · profissionais.js · servicos.js
backend/          # reservado para a API (ainda vazio)
```

## Próximos passos

- [ ] Ligar Agendamentos e Dashboard aos dados cadastrados
- [ ] Implementar o backend (API e banco de dados)
