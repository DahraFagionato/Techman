# API Techman

## Tecnologias
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)
- [MySQL](https://www.mysql.com/)

---

## Como executar o projeto

### 1. Clonar o repositório
```bash
git clone <url-do-repositorio>
```
### 2. Instalar as dependências
```bash
npm install
```
### 3. Configurar as variavéis de ambiente
Crie um arquivo .env na raiz do projeto e adicione:
```env
DATABASE_URL="mysql://root:password@localhost:3306/techman"
```
### 4. Iniciar o MySQL
Certifique-se de que o servidor do MySQL (SGBD) está em execução.
### 5. Aplicar as migrações
```bash
npx prisma migrate dev --name init
```
### 6. Rodar o servidor em modo de desenvolvimento
```bash
npm run devnpm run dev
```