# Inventário de Biblioteca

Sistema simples para controle de inventário de livros, com autenticação, exportação e integração com a Biblioteca Nacional.

## Funcionalidades
- Cadastro de livros com ISBN, título, autor, ano, gênero, quantidade e notas
- Busca automática de dados do livro pelo ISBN (Biblioteca Nacional)
- Controle de empréstimos e devoluções
- Exportação para XLS e PDF
- Autenticação de usuários (Supabase)
- Registro do colaborador que cadastrou cada livro

## Como usar
1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/Inventb.git
   ```
2. **Abra o arquivo `index.html` em seu navegador.**
3. **Configure o Supabase:**
   - Crie um projeto em [Supabase](https://app.supabase.com)
   - No menu SQL Editor, rode o script de criação de tabelas (veja no próprio app)
   - Habilite autenticação por email
   - Copie a URL do projeto e a anon key e preencha no app
4. **Cadastre-se e faça login para começar a usar.**

## Dependências externas
- [Supabase JS](https://supabase.com/docs/reference/javascript)
- [SheetJS](https://sheetjs.com/)
- [jsPDF](https://github.com/parallax/jsPDF) + [autotable](https://github.com/simonbengtsson/jsPDF-AutoTable)


## Observações Importantes de Segurança
- **Nunca exponha sua chave API do Supabase em repositórios públicos, sites ou fóruns.**
- Sempre preencha a URL e a chave manualmente no campo do app.
- Se você expôs sua chave por engano, gere uma nova no painel do Supabase.
- O app funciona 100% client-side.
- Para uso em produção, ajuste as políticas de segurança do Supabase conforme necessário.

---

Desenvolvido por [Seu Nome].
