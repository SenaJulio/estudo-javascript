# Capítulo 05 – Eventos, DOM e Interatividade

## ✅ Tópicos Estudados
- [x] Manipular elementos HTML via JavaScript
- [x] Eventos de clique, teclado, mouse
- [ ] Alterar estilos via script
- [ ] Criar interações simples

## 💡 Conceitos importantes
- O DOM representa a estrutura da página como um objeto manipulável.
- Eventos conectam o mundo real (ações do usuário) com o código.
- `document.querySelector` é a chave mágica pra acessar elementos.

## 💻 Código base
```html
<button onclick="clicou()">Clique aqui</button>

<script>
function clicou() {
  alert("Você clicou!");
}
</script>
```

## 🤔 Dúvidas
- Quando usar `addEventListener` ao invés de `onclick`?

## 🧠 Resumo em 1 frase
> O DOM é a ponte entre o HTML estático e a mágica interativa do JavaScript.
