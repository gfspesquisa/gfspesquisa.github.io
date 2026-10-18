# Site acadêmico — Gabriel Felix da Silva

Site feito com **Hugo Blox** e hospedado gratuitamente no **GitHub Pages**. Ele já vem com:

- páginas **Início, Sobre, Pesquisa, Publicações, Notícias, Equipe e Contato**, em português;
- **painel de edição com login** em `/admin`, para você e os colaboradores editarem sem mexer em código;
- busca interna, modo escuro e layout que funciona no celular.

Os visitantes só leem o site. Para editar, a pessoa precisa entrar no painel com uma conta do GitHub **que você autorizou**.

---

## Passo 1: Criar a conta e o repositório no GitHub

1. Crie uma conta em <https://github.com> (se ainda não tiver). O nome de usuário vai aparecer no endereço do site.
2. Clique em **New repository** e use exatamente este nome:
   **`gfspesquisa.github.io`**.
3. Deixe o repositório **Public** e clique em **Create repository**.

> Com esse nome, o site fica em `https://gfspesquisa.github.io`. Com outro nome, ele fica em uma subpasta, e as imagens enviadas pelo painel podem não aparecer.

## Passo 2: Enviar os arquivos

O jeito mais seguro é o **GitHub Desktop** (<https://desktop.github.com>):

1. Instale o programa, entre com sua conta e clone o repositório que você criou.
2. Descompacte o `.zip` deste site e **copie todo o conteúdo para dentro da pasta do repositório**.
   Inclua a pasta oculta **`.github`**, que faz o site ser publicado automaticamente.
   - Windows: ative "Itens ocultos" na aba Exibir do Explorador de Arquivos.
   - Mac: no Finder, aperte `Cmd + Shift + .` para mostrar arquivos ocultos.
3. No GitHub Desktop, escreva uma mensagem (ex.: "primeira versão do site"), clique em **Commit to main** e depois em **Push origin**.

## Passo 3: Seu usuário já está configurado

O usuário **gfspesquisa** já está preenchido em `config/_default/hugo.yaml` (`baseURL`) e em `static/admin/config.yml` (`repo`). Não precisa mudar nada aqui.

## Passo 4: Ligar o GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Build and deployment → Source**, escolha **GitHub Actions**.
3. Abra a aba **Actions** e espere o processo "Deploy website to GitHub Pages" ficar verde (cerca de 2 a 4 minutos).
4. Acesse **`https://gfspesquisa.github.io`**. 🎉

A partir de agora, **toda alteração salva no repositório (pelo painel ou não) republica o site sozinha** em poucos minutos.

## Passo 5: Entrar no painel de edição

1. Acesse **`https://gfspesquisa.github.io/admin/`**.
2. Clique em **Entrar usando token de acesso** (*Sign In Using Access Token*).
3. Para criar o token, no GitHub vá em **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**:
   - **Repository access**: *Only select repositories* → escolha o repositório do site;
   - **Permissions → Repository permissions → Contents**: **Read and write**;
   - defina uma validade (ex.: 1 ano) e gere o token.
4. Copie o token, cole no painel e entre. O navegador lembra do login.

> Trate o token como uma senha: não compartilhe e não publique.

No painel você encontra:

- **Publicações**: resumos, artigos e outros trabalhos, com DOI e links para a fonte original;
- **Pesquisa (projetos)**: os cartões da página Pesquisa;
- **Notícias**: novidades, eventos e prêmios;
- **Equipe (perfis)**: o seu perfil (arquivo `me`) e o de cada colaborador;
- **Páginas → Contato**: endereço, e-mail e redes.

Ao clicar em **Salvar**, a alteração vai para o GitHub e o site é atualizado em alguns minutos.

## Passo 6: Dar acesso aos colaboradores

1. No repositório, vá em **Settings → Collaborators → Add people** e convide pela conta do GitHub de cada pessoa.
2. Depois de aceitar o convite, cada colaborador cria o **próprio token** (Passo 5) e entra no painel.
3. Para tirar o acesso de alguém, remova a pessoa na mesma tela.

Quem não for colaborador não consegue salvar nada, mesmo que abra o `/admin`.

## Passo 7 (opcional): Botão "Entrar com GitHub", sem token

Se os colaboradores acharem o token complicado, dá para ativar o login direto com a conta do GitHub. É grátis, mas exige uma conta na Cloudflare:

1. Siga as instruções do projeto **sveltia-cms-auth**: <https://github.com/sveltia/sveltia-cms-auth>
   (publicar o Worker na Cloudflare → criar um OAuth App no GitHub → colar o *Client ID* e o *Client Secret* no Worker).
2. Em `static/admin/config.yml`, apague o `#` da linha `base_url:` e coloque o endereço do seu Worker.

---

## Site em dois idiomas (português e inglês)

O site tem versão em **português** (`https://gfspesquisa.github.io/`) e em **inglês** (`https://gfspesquisa.github.io/en/`). O visitante troca de idioma pelo seletor no canto superior direito, e cada página leva à sua equivalente no outro idioma.

**No painel**, cada item mostra os dois idiomas lado a lado:

- **Pesquisa, Notícias, Equipe e Contato:** escreva o texto em português e depois em inglês. Campos como data, imagem e links são copiados sozinhos para o inglês.
- **Publicações:** ficam no idioma original em que foram publicadas e aparecem iguais nas duas versões. Basta cadastrar uma vez.
- **Equipe:** no campo "Grupo", use o nome em português na versão PT (ex.: Orientação) e o equivalente em inglês na versão EN (ex.: Supervision).

**Nos arquivos**, a versão em inglês fica ao lado da portuguesa: `index.md` (PT) e `index.en.md` (EN); `sobre.md` e `sobre.en.md`. Os perfis em inglês ficam em `data/en/authors/`, e os menus em `config/_default/menus.pt.yaml` e `menus.en.yaml`.

## Primeiros ajustes no conteúdo

- [ ] **Foto de perfil**: envie uma foto quadrada com o nome `me.jpg` para `assets/media/authors/` (no GitHub: *Add file → Upload files*, ou pelo painel no campo "Foto" do seu perfil, com o arquivo já renomeado para `me.jpg`).
- [ ] **Lattes**: no seu perfil, adicione um link com o ícone "Lattes".
- [ ] **Datas da formação e experiência**: preencha no seu perfil, se quiser mostrá-las.
- [ ] **Apague os modelos**: as duas publicações "[MODELO]" e o colaborador "Nome do(a) Colaborador(a)". No painel, abra o item e use **Excluir**.
- [ ] **Imagens dos projetos**: no painel, em cada projeto, use "Imagem de capa".
- [ ] **Revise os textos dos projetos** e confirme com seus orientadores o que pode ser divulgado antes da publicação.

## Importar publicações do ORCID automaticamente (opcional)

1. No ORCID, em *Works*, selecione os trabalhos e exporte em **BibTeX**.
2. Renomeie o arquivo para **`publications.bib`** e envie para a **raiz** do repositório.
3. Em **Settings → Actions → General**, marque *Allow GitHub Actions to create and approve pull requests*.
4. O GitHub cria automaticamente um *Pull Request* com as publicações convertidas. Revise e clique em **Merge**.

## Domínio próprio (opcional)

Se comprar um domínio (ex.: `gabrielfelix.com.br`), configure em **Settings → Pages → Custom domain** e troque o `baseURL` em `config/_default/hugo.yaml`.

## Onde fica cada coisa (para quem quiser editar os arquivos)

| O quê | Arquivo |
|---|---|
| Seu perfil (bio, formação, experiência, links) | `data/authors/me.yaml` (PT) e `data/en/authors/me.yaml` (EN) |
| Colaboradores | `data/authors/*.yaml` |
| Página inicial (ordem das seções) | `content/_index.md` |
| Publicações | `content/publications/<nome>/index.md` |
| Projetos de pesquisa | `content/pesquisa/<nome>/index.md` |
| Notícias | `content/blog/<nome>/index.md` |
| Menu | `config/_default/menus.pt.yaml` e `menus.en.yaml` |
| Nome do site, cores e fontes | `config/_default/params.yaml` |
| Configuração do painel | `static/admin/config.yml` |
| Traduções de textos do tema | `i18n/pt-br.yaml` |

### Testar no computador (opcional)

Precisa de [Hugo extended](https://gohugo.io/installation/) (versão 0.162 ou mais nova), [Go](https://go.dev/dl/) e [Node.js](https://nodejs.org/):

```bash
npm install -g pnpm
pnpm install
hugo server
```

Depois abra <http://localhost:1313>.

### Observação técnica

`layouts/_partials/functions/build_links.html` é uma cópia corrigida de um arquivo do tema. O original dá erro no Hugo 0.162 quando uma página tem links. Se uma atualização futura do Hugo Blox corrigir o problema, esse arquivo pode ser apagado.
