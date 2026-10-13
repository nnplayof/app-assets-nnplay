# 🖼️ app-assets-nnplay

Repositório central de assets estáticos e banco de imagens para o aplicativo **NN Play**.

Este repositório armazena e distribui mídias estáticas consumidas remotamente pelo aplicativo, permitindo a atualização instantânea de banners e elementos visuais sem a necessidade de lançar novas versões ou compilar o app novamente.

---

## 📐 Padrões Técnicos de Imagem

Para manter a consistência visual e o alinhamento da interface:

* **Dimensões dos Banners:** `3840 x 1400 px` (formato ultrawide / 4K adaptado)
* **Formatos Recomendados:** `.png` (para nitidez e transparência) ou `.webp` / `.jpg` otimizados para web.
* **Nomenclatura:** Use letras minúsculas e hífens, sem espaços ou caracteres especiais (ex: `banner-principal.png`, `banner-ao-vivo.png`).

---

## 🔗 Estrutura dos Links (CDN jsDelivr)

As imagens são consumidas no aplicativo via CDN para garantir alta disponibilidade, entrega rápida e link limpo:

```text
[https://cdn.jsdelivr.net/gh/](https://cdn.jsdelivr.net/gh/)<SEU-USUARIO>/app-assets-nnplay@latest/<PASTA>/<NOME-DA-IMAGEM>
