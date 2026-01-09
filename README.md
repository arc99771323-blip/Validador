# Validador de CPF e Placa

Uma página simples (HTML + CSS + JS) para validar **CPF** e **placa de veículo** (padrão antigo `ABC-1234` e Mercosul `ABC1D23`).

## 🚀 Como rodar localmente

1. Faça o download dos arquivos deste repositório.
2. Abra o arquivo `index.html` diretamente no seu navegador (duplo clique já funciona).

> Não há dependências externas; é tudo client-side.

## 🌐 Publicar com GitHub Pages

1. Crie um repositório público no GitHub (ex.: `validador-cpf-placa`).
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha a branch `main` e a pasta `/(root)`.
5. Clique em **Save** e aguarde alguns segundos.
6. Acesse: `https://SEU_USUARIO.github.io/validador-cpf-placa/`.

## 🧪 Como usar

- **CPF**: digite 11 dígitos; o script calcula os dígitos verificadores e formata como `000.000.000-00`.
- **Placa**: aceite os padrões `ABC-1234` (antigo) ou `ABC1D23` (Mercosul). O campo converte para maiúsculas e formata quando aplicável.

## ✨ UI/UX

- Layout em "glassmorphism" com sombras e gradientes.
- Feedback visual imediato: ícones de sucesso/erro e caixas de resultado com cores.
- Acessibilidade: `aria-label`, `aria-live` e `role="region"` para melhor leitura por leitores de tela.

## 👤 Créditos

Desenvolvido por **André Moura (CDD Araçatuba)**.

## 📄 Licença

Este projeto é disponibilizado sob a licença MIT. Sinta-se à vontade para usar e adaptar.
