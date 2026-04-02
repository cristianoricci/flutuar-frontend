# 🪂 Flutuar Parapente — Frontend

Interface web para gernciamento de alunos interessados em curso de parapente.
Desenvolvida com HTML, CSS e JavaScript.

## Descrição

Single Page Applicattion (SPA) que consome a API do backend Flutuar Parapente.
Permite cadastrar, visualizar, editar, filtrar e remover alunos interessados nos cursos.

### Cursos disponíveis

| Curso | Cor |
|-------|-----|
| Iniciante | 🔵 Azul |
| Cross | 🟡 Amarelo |
| Voo Duplo | 🟢 Verde |

## Como executar

### Pré-requisito

O backend deve ser rodado em `http://localhost:5000`.
Consute o repositório do backend para instruções de instalação.

### Abrir o frontend
```bash
xdg-open index.html
```
Ou clique duas vezes no arquivo `index.html` .

> Não é necessário nenhum servidor local, extensão ou dependência adicional.

## Rotas da API consumidas

| Rota | Quando é chamada |
|------|------------------|
| GET /buscar_alunos | Ao carregar a página |
| GET /buscar_por_curso | Ao clicar em um filtro |
| GET /buscar_aluno/<id> | Ao Ccicar em Editar |
|POST /cadastrar_aluno | Ao salvar novo aluno |
|PUT /atualizar_aluno/<id> | Ao salvar edição |
|DELETE /deletar_aluno/<id> | Ao confirmar a remoção |


## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript