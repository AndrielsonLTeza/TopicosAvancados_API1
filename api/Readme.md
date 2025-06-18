Detalhes:

Reconstrói a aplicação via docker-compose up --build.

Expõe a API em localhost:8080.

Suporta escala futura com banco de dados via depends_on.

🛠 Instruções para uso
Coloque os dois arquivos na raiz do projeto (pom.xml).

Construa e rode:

bash
Copiar
Editar
docker-compose up --build
Acesse a API em http://localhost:8080.

🚀 Próximos passos (opcionais)
Inserir variáveis de ambiente no docker-compose para conexão com banco, endpoints externos, etc.

Adicionar volume ou container adicional (PostgreSQL, Redis).

Ajustar perfil Spring (application-prod.yml) com DB, logging, etc.