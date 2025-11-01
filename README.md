# gustavosaturnino.github.io
Profissional
# 1️⃣ Navegue até o repositório local
cd gustavosaturnino.github.io

# 2️⃣ Mova os arquivos da pasta Rajada-QR para a raiz
git mv Rajada-QR/index.html .
git mv Rajada-QR/Organograma-Profissional.pdf .

# 3️⃣ Apague a pasta Rajada-QR (vazia agora)
rmdir Rajada-QR

# 4️⃣ Commit das alterações
git commit -m "Mover index.html e PDF para a raiz para GitHub Pages"

# 5️⃣ Enviar alterações para o GitHub
git push origin main
