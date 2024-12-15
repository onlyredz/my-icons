# Icons Repository 🗂

Este repositório contém ícones no formato **SVG** e **PNG** que podem ser usados em projetos HTML, Markdown ou qualquer outra aplicação web. Os ícones estão sem cores definidas, permitindo que você personalize as cores conforme necessário.

---

## 🌟 **Como Usar**

1. **Encontre o ícone desejado:**  
   Navegue pelos arquivos do repositório na pasta `icons` e escolha o ícone que deseja usar.

2. **Copie o link do ícone:**  
   Para acessar diretamente o arquivo, use o link no seguinte formato:

   ```
   https://raw.githubusercontent.com/onlyredz/my-icons/main/icons/example-icon.svg
   ```

3. **Insira o ícone no seu projeto e defina a cor:**  
   Use o ícone no HTML ou CSS e personalize sua cor com `fill` (para ícones em SVG). Exemplos:

   **HTML com cor personalizada:**
   ```html
   <svg width="50" height="50" fill="#E34F26">
       <use xlink:href="https://raw.githubusercontent.com/onlyredz/my-icons/main/icons/example-icon.svg#icon-id"></use>
   </svg>
   ```

   **Ou diretamente no `img` com cor padrão:**
   ```html
   <img src="https://raw.githubusercontent.com/onlyredz/my-icons/main/icons/example-icon.svg" alt="Example Icon" style="width: 50px; height: 50px; fill: #E34F26;">
   ```

4. **Use as cores oficiais do Simple Icons:**  
   As cores oficiais das marcas estão disponíveis no site [Simple Icons](https://simpleicons.org). Copie o código hexadecimal da cor desejada e aplique no atributo `fill` do SVG.

---

## 📂 **Estrutura do Repositório**

Todos os ícones estão localizados na pasta `icons` dentro deste repositório para facilitar o acesso. Certifique-se de usar os nomes dos arquivos corretamente ao copiá-los.

---

## 🎨 **Como Personalizar a Cor**

### 1. **Usando o atributo `fill` no SVG**
Se estiver usando o conteúdo SVG diretamente no HTML, adicione o atributo `fill` para definir a cor do ícone:

```html
<svg width="50" height="50" fill="#0078D7">
    <use xlink:href="https://raw.githubusercontent.com/onlyredz/my-icons/main/icons/example-icon.svg#icon-id"></use>
</svg>
```

### 2. **Aplicando cor via CSS**
Se estiver usando o ícone como `img`, você pode colorir usando CSS:

```css
img {
    width: 50px;
    height: 50px;
    filter: invert(0%) sepia(100%) saturate(5000%) hue-rotate(200deg) brightness(100%) contrast(90%);
}
```

---

## 🤝 **Como Contribuir**

Contribuições são muito bem-vindas! Siga os passos abaixo para colaborar:

1. **Faça um fork deste repositório:**  
   Clique em **Fork** no canto superior direito da página para criar uma cópia deste repositório no seu GitHub.

2. **Clone o repositório forkado:**  
   Use o comando abaixo no terminal:
   ```bash
   git clone https://github.com/<seu-usuario>/my-icons.git
   ```

3. **Crie uma branch para suas alterações:**  
   ```bash
   git checkout -b minha-nova-feature
   ```

4. **Adicione ou atualize ícones:**  
   - Certifique-se de que os arquivos estejam no formato **SVG** e **PNG**, e sem cor definida.
   - Mantenha os nomes dos arquivos descritivos e padronizados (ex.: `icon-nome.svg` ou `icon-nome.png`).

5. **Faça um commit das alterações:**  
   ```bash
   git add .
   git commit -m "Adicionei os ícones HTML5 SVG e PNG"
   ```

6. **Envie suas alterações para o GitHub:**  
   ```bash
   git push origin minha-nova-feature
   ```

7. **Abra um Pull Request:**  
   Vá até o repositório original e clique em **New Pull Request**. Explique as alterações que você fez e envie o PR.

---

## 💬 **Dúvidas ou Sugestões**

Caso tenha dúvidas ou sugestões, entre em contato comigo abrindo uma issue neste repositório ou me encontre em [GitHub](https://github.com/onlyredz).

---

✨ **Feito para praticidade por [REDZ](https://github.com/onlyredz)** ✨

_Por que usar SVG sem cor?_
- **Flexibilidade:** Permite que os usuários apliquem cores específicas conforme o design do projeto.
- **Tamanho reduzido:** Ícones em SVG são leves e escaláveis.
- **Personalização com Simple Icons:** Fácil de combinar com cores oficiais usando os códigos HEX disponíveis no site.
