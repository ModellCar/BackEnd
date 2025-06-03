Este é o backend da aplicação Catálogo de Carros, desenvolvido com Java SpringBoot. Ele faz a integração com a CarImage API para obter informações e imagens de carros e permite gerenciar uma lista de carros favoritos com operações locais de CRUD (Criar, Ler, Atualizar e Deletar).

✨ Funcionalidades
📜 Listar Carros: Busca e exibe uma lista de carros da API externa CarImage.

➕ Adicionar Carro: Adiciona carros aos favoritos (simulado no backend).

✏️ Editar Carro: Permite atualizar informações de carros na lista local.

🗑️ Deletar Carro: Remove carros da lista local de favoritos.

🌐 Integração com API: Busca de dados externos de carros através da API CarImage.

🚀 Tecnologia
```
Java 21: Linguagem de programação principal
Spring Boot 3.2.1: Framework para desenvolvimento web
MySQL: Banco de dados relacional
Maven: Gerenciador de dependências
JPA/Hibernate: ORM para persistência de dados
REST: Arquitetura da API
```


✅ Pré-requisitos
Node.js (versão 16 ou superior) instalado.

Uma chave da API CarImage 🔑 (obtenha no site da API CarImage).

🧑‍💻 Instalação
1️⃣ Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/lucasdev077/Projeto-Mobile
cd Projeto-Backend

2️⃣ Instale as dependências:
bash
Copiar
Editar
npm install

3️⃣ Crie um arquivo .env na raiz do projeto e adicione sua chave da API CarImage:
env
Copiar
Editar
CAR_IMAGE_API_KEY=sua_chave_aqui


🔗 Rotas da API
Método	Endpoint	Descrição
```
GET	/cars	Lista carros obtidos da API CarImage
GET	/favorites	Lista todos os carros favoritos
POST	/favorites	Adiciona um carro aos favoritos
PUT	/favorites/:id	Edita informações de um carro favorito
DELETE	/favorites/:id	Remove um carro da lista de favoritos
```

🌐 Integração com a API CarImage
A API CarImage é usada para obter os dados e imagens dos carros.

As ações de adicionar, editar e deletar são executadas localmente, simuladas no backend, pois a API externa é somente leitura.

![image](https://github.com/user-attachments/assets/0f884f78-5fe2-4d85-917f-35642cc96683)


