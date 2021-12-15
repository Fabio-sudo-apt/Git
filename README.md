## Git
 - Primeiros passos

 1. git init - isso no repositorio local
 2. git status
 3. git add * - Adicione os arquivo do seu projeto no repositorio local
 4. git commit -m "Primeiro commit" - Fazendo o primeiro commit local
 5. posso subtituir a 3 e 4 por git commit -am "msg"
 6. git push origin main - adiciona os arquivos no repositorio remoto 

 - Git CLone
 1. git clone HTTP ou SSH - O clone Git é usado para copiar um repositório Git existente em um novo diretório local.


 - SSH ou Token

 1. ssh-keygen -t ed25519 -C (user)

 2. Procura a pasta da chave pub e pri

 3. cat id_ed25519.pub

 4. eval $(ssh-agent -s)

