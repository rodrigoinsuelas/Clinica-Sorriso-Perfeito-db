# Inicializa o repositório Git local
git init

# Adiciona todos os arquivos da pasta ao gerenciamento do Git
git add .

# Faz o primeiro commit
git commit -m "feat: estrutura inicial do MER e diagrama da clinica"

# Define a branch principal como main
git branch -M main

# Vincula o repositório local ao repositório criado no GitHub
git remote add origin https://github.com/SEU-USUARIO/clinica-sorriso-perfeito-db.git

# Envia os arquivos para o GitHub
git push -u origin main
