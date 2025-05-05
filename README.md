
---

````markdown
# 🌐 Introdução ao HTML

HTML significa **HyperText Markup Language**.  
É a **linguagem usada para criar páginas na internet**.  

Vamos entender isso com um exemplo bem simples e visual!

---

## 🧱 Estrutura Básica do HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Página Aleatória</title>
</head>
````

🔹 `<!DOCTYPE html>` → Diz que o documento é em HTML5
🔹 `<html>` → É o elemento raiz de toda a página
🔹 `<head>` → Contém informações invisíveis na tela (ex: título da aba)
🔹 `<title>` → Nome que aparece na aba do navegador

---

## 🖥️ Corpo da Página

```html
<body>
  <h1>Bem-vindo à Página Aleatória!</h1>
  <p>Clique no botão para mudar a cor de fundo:</p>
  <button onclick="mudarCor()">Mudar Cor</button>
</body>
```

🔹 `<body>` → Tudo aqui aparece na tela do navegador
🔹 `<h1>` → Título principal
🔹 `<p>` → Um parágrafo
🔹 `<button>` → Um botão interativo

---

## 🎨 Estilizando com CSS (Visual)

```html
<style>
  body {
    font-family: Arial;
    text-align: center;
  }
  button {
    padding: 10px;
    cursor: pointer;
  }
</style>
```

🎨 Aqui usamos **CSS** para deixar a página mais bonita:

* Texto centralizado
* Fonte personalizada
* Botão com espaço e cursor de mãozinha

---

## ⚙️ Tornando Interativo com JavaScript

```html
<script>
  function mudarCor() {
    const cores = ["#f9c74f", "#90be6d", "#f94144", "#577590", "#f9844a"];
    const corAleatoria = cores[Math.floor(Math.random() * cores.length)];
    document.body.style.backgroundColor = corAleatoria;
  }
</script>
```

🧠 Essa função faz o seguinte:

1. Escolhe uma **cor aleatória**
2. Muda a **cor do fundo da página**
   Tudo isso acontece quando clicamos no botão!

---

## ✅ Conclusão

🧩 O HTML sozinho mostra o conteúdo.
🎨 O CSS cuida do visual.
⚙️ O JavaScript traz interatividade.

Com esses três juntos, dá pra criar **sites completos**!

---

```

---


