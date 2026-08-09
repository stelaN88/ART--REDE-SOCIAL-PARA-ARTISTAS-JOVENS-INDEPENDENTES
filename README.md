# ART ✦ — Rede Social para Artistas Jovens Independentes

ART é uma rede social desenvolvida como Trabalho de Conclusão de Curso (TCC), voltada para artistas jovens independentes compartilharem suas obras, se conectarem e se inspirarem mutuamente.

---

## 📱 Sobre o projeto

A plataforma permite que artistas publiquem fotos de seus trabalhos, interajam com outros usuários através de curtidas e comentários, troquem mensagens e descubram novos talentos. O design foi pensado para mobile, com uma interface limpa e intuitiva inspirada em redes sociais modernas.

---

## ✨ Funcionalidades

- **Cadastro e login** com email e senha
- **Feed principal** com posts em grade de 2 colunas
- **Abas "Para você" e "Seguindo"** no feed
- **Publicar posts** com imagem e descrição
- **Curtir e comentar** posts
- **Lightbox** ao clicar em uma foto — fundo desfocado com a própria imagem
- **Marca d'água** automática nas fotos com o nome do autor
- **Busca de usuários** por nome
- **Grade de descoberta** na tela de busca
- **Perfil do usuário** com posts, seguidores e curtidas
- **Perfil de outros usuários** com botão Seguir/Seguindo e chat
- **Editar perfil** — nome, username, bio, categoria e foto
- **Sistema de seguir/deixar de seguir** usuários
- **Mensagens diretas** entre usuários em tempo real
- **Notificações** de curtidas, comentários, novos seguidores e mensagens
- **Novos seguidores** dos últimos 7 dias

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização e responsividade |
| JavaScript | Lógica e interatividade |
| Supabase | Banco de dados, autenticação e storage |
| Git / GitHub | Versionamento do código |

---

## 📁 Estrutura de arquivos

```
ART-rede-social/
├── index.html           # Home — feed principal
├── login.html           # Login e cadastro
├── perfil.html          # Perfil do usuário (próprio e de outros)
├── edit-profile.html    # Editar perfil
├── search.html          # Busca de usuários e descoberta
├── notificacoes.html    # Notificações
├── novos-seguidores.html# Novos seguidores
├── mensagens.html       # Lista de conversas
├── chat.html            # Chat entre usuários
└── imagens/             # Imagens estáticas do projeto
    └── tinta.jpeg       # Fundo da tela de login
```

---

## 🗄️ Banco de dados (Supabase)

| Tabela | Descrição |
|---|---|
| `perfis` | Dados do perfil do usuário |
| `posts` | Posts publicados |
| `curtidas` | Curtidas nos posts |
| `comentarios` | Comentários nos posts |
| `follows` | Relações de seguidor/seguido |
| `mensagens` | Mensagens diretas entre usuários |
| `notificacoes` | Notificações do sistema |

---

## 🚀 Como rodar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/stelaN88/ART--REDE-SOCIAL-PARA-ARTISTAS-JOVENS-INDEPENDENTES.git
```

2. Abra a pasta no VS Code

3. Instale a extensão **Live Server**

4. Clique com o botão direito no `login.html` → **Open with Live Server**

5. Acesse `http://localhost:5500/login.html`

> O projeto usa o Supabase como backend — as credenciais já estão configuradas no código para fins de desenvolvimento do TCC.

---

## 👩‍💻 Autora

Desenvolvido por **Stela MARUANI NATUS** como Trabalho de Conclusão de Curso da Escola Técnica Estadual Monteiro Lobato.