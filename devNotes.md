# Comandos rodados no projeto

➜ npm create vite@latest
Need to install the following packages:
  create-vite@latest
Ok to proceed? (y) y
✔ Project name: … web
✔ Select a framework: › react
✔ Select a variant: › react-ts

npm install
➜ npm install tailwindcss -D
➜ npx tailwindcss init -p // Instala o postcss que vai ficar atualizando nosso app quando css for alterado.
➜ npm install -D tailwindcss postcss autoprefixer 
➜ npm install phosphor-react
➜ npm install @headlessui/react // Ferramenta de acessibilidade dos criadores do tailwind
➜ npm install -D @tailwindcss/forms //Plugin do tailwind para formulários (tem que add em tailwind.config.js)
➜ npm install -D tailwind-scrollbar //Plugin para tratar as scrollbar (tem que add em tailwind.config.js)
➜ npm install html2canvas 
➜ npm install axios

## Deploy
- Configurar variáveis de ambiente.





## Notes
Vite = Ferramenta que permite que nosso navegador entenda o nosso javascript mais moderna,
já que os navegadores nem sempre conseguem acompanhar a evolução.
Ele substitui o babel, mas ele não precisa substituir o webpack, pois agora os navegadores estão aceitando os imports no javascript.

React 
Toda função retornando um html é um componente
Sua primeira letra deve ser Maiúscula.

<!-- <img src="">             src = atributo -->
<!-- <ReactButton text="" />  text = propriedade -->


<!-- 
overflow: hidden; ou overflow-hidden,  qualquer texto ou conteúdo que sobreponha o tamanho máximo daquele elemento, vai ficar invisível 
-->