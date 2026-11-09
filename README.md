# 🎵 Sistema Musical

O **Sistema Musical** é uma aplicação web para gerenciamento de catálogo fonográfico, permitindo o controle de acesso de usuários, cadastro de artistas e organização de uma biblioteca musical completa com links integrados ao YouTube.

---

## 🚀 Funcionalidades

### 🔐 Autenticação
* **Tela de Login:** Restringe o acesso ao sistema apenas a usuários credenciados.

### 🎛️ Painel Principal (Menu)
* **Navegação Centralizada:** Direcionamento rápido para as três áreas principais do sistema.
* **Logoff:** Opção segura para encerrar a sessão do usuário.

### 🎤 Gerenciamento de Artistas
* **Cadastro Completo:** Inclusão de nome, gênero musical, país de origem e upload de foto de perfil (formatos JPG/PNG até 5MB).
* **Listagem em Tempo Real:** Tabela com os artistas cadastrados (ex: *Djavan*, *Marisa Monte*).
* **Controle de Dados:** Opções para editar informações, excluir registros ou acessar diretamente as músicas vinculadas ao artista.

### 🎵 Cadastro de Músicas
* **Vínculo Dinâmico:** Associação da música a um artista previamente cadastrado via menu de seleção.
* **Formulário Detalhado:** Campos para título, álbum, gênero musical, letra da música e upload de capa do álbum (formatos JPG/PNG até 5MB).
* **Integração de Mídia:** Validação e inserção de links diretos de vídeos do YouTube.

### 🎼 Biblioteca Musical
* **Filtros Avançados:** Busca geral de faixas e filtragem refinada por artista ou gênero musical.
* **Visualização Geral:** Listagem detalhada exibindo capa, título, artista, álbum e gênero de cada música.
* **Ações Rápidas:** Botão para assistir ao clipe no YouTube, além de atalhos para edição e exclusão de faixas.

---

## 🛠️ Tecnologias Sugeridas para o Escopo
*(Ajuste esta seção de acordo com a stack real do projeto)*

* **Front-end:** HTML5, CSS3 (ou frameworks como Tailwind/Bootstrap) e JavaScript.
* **Back-end:** Node.js / PHP / Python (Processamento de formulários e upload de arquivos).
* **Banco de Dados:** MySQL / PostgreSQL (Estrutura relacional para o vínculo Artista ──► Música).

---

## 🔑 Credenciais de Teste

Para homologação e testes rápidos do sistema no ambiente local:

* **Usuário:** `admin`
* **Senha:** `123`

---

## 📂 Estrutura de Navegação do Sistema

```text
[ Login ]
   │
   └───► [ Menu Principal ]
             │
             ├──► [ Gerenciar Artistas ] ──► (Cadastrar / Editar / Excluir)
             │
             ├──► [ Cadastrar Músicas ]   ──► (Formulário de Inclusão)
             │
             └──► [ Biblioteca Musical ]  ──► (Filtros / Listagem / Player)
```


