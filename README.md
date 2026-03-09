# API Escola - Node.js + Express
API REST simples para gerenciar alunos e professores

## Pré-requisitos
- Node.js instalado

## Como rodar
```bash
npm i
```

### Iniciar o servidor
```bash
npm i
```

### Acessar
Abra o navegador em: `http://localhost:3000`


## Endpoints

### Alunos

| Método | Endpoit | Descrição |
|--------|----------|-----------|
| GET | `/alunos` | Lista todos os alunos |
| GET | `/alunos:id` | Buscar um aluno específico |
| POST | `/alunos` | Cria um novo aluno |
| PUT | `/alunos/:id` | Atualizar um aluno |
| DELETE | `/alunos/:id` | Remove um aluno |

### Professores

| Método | Endpoit | Descrição |
|--------|---------|-----------|
| GET | `/professores` | Lista todos os professores |
| POST | `/professores` | Cria um novo professor |
| PUT | `/professores/id:` | Atualizar um professor |
| DELETE | `/professores/:id` | Deleta um professor |

## Tecnologias
- Node.js
- Express

## Notas
- Os dados são armazenados em memórias (reiniciar o servidor apaga tudo)
