# Manual do Locatário · Acontece Imobiliária

Manual digital interativo para locatários da **Acontece Imobiliária** (Brasília-DF). Reúne, em um único arquivo, tudo o que o inquilino precisa saber — do início ao fim da locação — organizado por módulos, com busca, navegação por sumário e exportação em PDF.

🔗 **Acesse:** `https://<seu-usuario>.github.io/<seu-repositorio>/`

## ✨ Recursos

- **Leitura por módulos** — conteúdo em sanfonas (accordion) agrupadas por fase da locação: *Comece por aqui*, *Início da locação*, *Durante a locação* e *Fim da locação*.
- **Busca instantânea** — filtra os módulos por assunto (ex.: vistoria, reajuste, multa).
- **Sumário navegável** — índice clicável com rolagem suave.
- **Exportação em PDF** — gera o manual completo ou um módulo individual, com cabeçalho da marca.
- **Compartilhável por módulo** — cada tema tem link próprio (`#id`) para copiar e enviar.
- **100% responsivo** — feito para o celular, com identidade visual da Acontece aplicada.
- **Acessível** — respeita `prefers-reduced-motion` e usa marcação semântica.

## 🚀 Publicação no GitHub Pages

1. Faça o commit do `index.html` (e deste `README.md`) na branch principal do repositório.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione a branch (`main`) e a pasta `/ (root)`.
4. Salve. Em alguns instantes o manual estará disponível no endereço do Pages.

> Por estar nomeado como `index.html`, o GitHub Pages serve o manual automaticamente na raiz do repositório.

## 🗂️ Estrutura

```
.
├── index.html   # Manual completo (HTML + CSS + JS em arquivo único)
└── README.md
```

Tudo está autocontido em `index.html`: estilos, scripts, ícones (SVG inline) e o logotipo (PNG em base64). **Não há dependências externas além das fontes** (Google Fonts — Poppins) e nenhum build é necessário.

## 🎨 Identidade visual

| Elemento            | Valor                                  |
| ------------------- | -------------------------------------- |
| Verde da marca      | `#2C6E2E`                              |
| Verde escuro        | `#235724`                              |
| Fundo creme         | `#F5F0E5`                              |
| Tipografia          | Poppins                                |
| Logotipo            | Triangular "Acontece Imobiliária"      |

## 🛠️ Desenvolvimento

Por ser um arquivo único e estático, basta abrir o `index.html` no navegador. Para servir localmente (opcional):

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## 📞 Contato

**Acontece Imobiliária** · Brasília-DF
CLSW 302, Bloco B, Loja 57/67 — Setor Sudoeste
(61) 3344-4112 · [aconteceimobiliaria.com.br](https://aconteceimobiliaria.com.br)

---

> Este manual tem caráter informativo e orientativo. Em caso de divergência, prevalecem as cláusulas do contrato de locação e a Lei nº 8.245/91 (Lei do Inquilinato).
