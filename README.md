# VitaContábil — Landing Page

Site institucional do escritório de contabilidade **VitaContábil**, focado exclusivamente no atendimento a profissionais de saúde (médicos, dentistas, psicólogos, fisioterapeutas e outros). Atendimento 100% online.

---

## Visão geral

Página única (single page) em HTML, CSS e JavaScript puro — sem frameworks, sem dependências de build. Pode ser hospedada diretamente no GitHub Pages ou em qualquer servidor estático.

---

## Estrutura da página

| Seção | Âncora | Descrição |
|---|---|---|
| Início / Hero | `#inicio` | Headline principal, chamada para ação e badges de diferenciais |
| Serviços | `#servicos` | 6 cards com os serviços oferecidos |
| Sobre nós | `#sobre` | Apresentação dos sócios Luis Henrique e Ednaldo |
| Por que nós | `#por-que` | Diferenciais do escritório |
| Contato | `#contato` | Formulário de contato com campos de profissão e mensagem |

---

## Tecnologias

- **HTML5 / CSS3 / JavaScript** — sem frameworks
- **Google Fonts** — Playfair Display + Inter
- **Tabler Icons** — ícones via webfont (CDN)
- Sem dependências de `npm`, `node_modules` ou build

---

## Como usar

### Localmente

Basta abrir o arquivo no navegador:

```bash
# Clone o repositório (ou baixe o arquivo)
git clone https://github.com/seu-usuario/vitacontabil.git

# Abra no navegador
open index.html
```

### GitHub Pages

1. Renomeie o arquivo para `index.html`
2. Faça upload para o repositório
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `main` e `/ (root)`
5. O site estará disponível em `https://seu-usuario.github.io/vitacontabil`

---

## Personalização

### Trocar o nome do escritório

Busque por `VitaContábil` no arquivo e substitua pelo nome definitivo. O mesmo vale para `Vita<span>Contábil</span>` no logotipo do nav.

### Atualizar o WhatsApp

Localize a linha abaixo e substitua o número (formato: código do país + DDD + número):

```html
<a href="https://wa.me/5500000000000" target="_blank" rel="noopener">
```

Exemplo para o número (84) 99999-0000:

```html
<a href="https://wa.me/5584999990000" target="_blank" rel="noopener">
```

### Conectar o formulário a um backend

O formulário atualmente exibe apenas um feedback visual. Para receber os dados por e-mail ou salvar em planilha, substitua a função `handleSubmit` por uma chamada real. Opções simples e gratuitas:

- **[Formspree](https://formspree.io)** — adicione `action="https://formspree.io/f/SEU_ID"` na tag `<form>` e remova o `onsubmit`
- **Google Apps Script** — envie via `fetch` para uma Web App publicada na sua planilha

### Alterar cores

As cores principais estão definidas diretamente no CSS. Os valores centrais são:

| Uso | Cor |
|---|---|
| Verde principal (CTA, ícones) | `#5b9e7b` |
| Verde escuro (títulos, fundo CTA) | `#2e5f4a` |
| Verde claro (background) | `#f4faf7` |
| Verde menta (bordas, badges) | `#d4ece0` |

---

## Sócios

| | |
|---|---|
| **Luis Henrique** | Contador · Especialista em tributação PJ saúde |
| **Ednaldo** | Contador · Análise financeira e sistemas contábeis |

---

## Licença

Projeto privado. Todos os direitos reservados © 2025 VitaContábil.
