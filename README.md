# 🪂 Flutuar Parapente — Frontend

<<<<<<< HEAD
Interface web para gerenciamento de alunos interessados em curso de parapente.
Desenvolvida com HTML, CSS e JavaScript.
=======
Interface web para gerenciamento de alunos interessados em cursos de parapente.
Desenvolvida com HTML, CSS e JavaScript puro.
>>>>>>> daaae25 (docs: README finalizado e formatado)

## 📝 Descrição

Single Page Application (SPA) que consome a API do backend **Flutuar Parapente**.
A interface permite cadastrar, visualizar, editar, filtrar e remover alunos interessados nos cursos da escola.

### 🪂 Cursos Disponíveis

| Curso | Identificação Visual |
|-------|----------------------|
| **Iniciante** | 🔵 Azul |
| **Cross** | 🟡 Amarelo |
| **Voo Duplo** | 🟢 Verde |

## 🚀 Como Executar

### Pré-requisito

O backend deve estar em execução no endereço: `http://localhost:5000`.
Consulte o repositório do [backend](https://github.com/cristianoricci/flutuar-backend) para instruções de instalação.

### Abrir o Frontend

Como o projeto utiliza tecnologias nativas do navegador, basta abrir o arquivo principal:

```bash
# No terminal (Linux/Debian)
xdg-open index.html

Ou simplesmente clique duas vezes no arquivo index.html em seu gerenciador de arquivos.

    Nota: Não é necessário instalar dependências ou configurar servidores locais de desenvolvimento (como Node.js) para este frontend.

<<<<<<< HEAD
| Rota | Quando é chamada |
|------|------------------|
| GET /buscar_alunos | Ao carregar a página |
| GET /buscar_por_curso | Ao clicar em um filtro |
| GET /buscar_aluno/<id> | Ao Clicar em Editar |
|POST /cadastrar_aluno | Ao salvar novo aluno |
|PUT /atualizar_aluno/<id> | Ao salvar edição |
|DELETE /deletar_aluno/<id> | Ao confirmar a remoção |
=======
🔌 Integração com a API
>>>>>>> daaae25 (docs: README finalizado e formatado)

Abaixo estão as rotas consumidas para o funcionamento da interface:
Rota	Ação no Sistema
GET /buscar_alunos	Carregamento inicial da lista
GET /busca_por_curso	Aplicação de filtros de curso
GET /buscar_aluno/<id>	Busca de dados para edição
POST /cadastrar_aluno	Envio de novo formulário
PUT /atualiza_aluno/<id>	Salvamento de alterações
DELETE /deletar_aluno/<id>	Remoção de registro
🛠️ Tecnologias Utilizadas

    HTML5 (Estrutura)

<<<<<<< HEAD
- HTML5
- CSS3
- JavaScript
=======
    CSS3 (Estilização e Layout)

    JavaScript (Lógica de consumo de API e manipulação do DOM)
>>>>>>> daaae25 (docs: README finalizado e formatado)
