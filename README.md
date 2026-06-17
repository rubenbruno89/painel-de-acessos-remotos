# 🔐 Painel de Acessos Remotos

> Um gerenciador de credenciais de acesso remoto (AnyDesk, TeamViewer, HostDesk, etc.) que funciona direto no navegador, usando Excel como backup.

[![Acessar Demo](https://img.shields.io/badge/🌐_Acessar_Demo-Live-blue?style=for-the-badge)](https://rubenbruno89.github.io/painel-de-acessos-remotos/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📖 Sobre o Projeto

O **Painel de Acessos Remotos** é uma aplicação web leve e responsiva, desenvolvida para facilitar o gerenciamento de credenciais de softwares de acesso remoto como **AnyDesk**, **TeamViewer**, **HostDesk**, **Chrome Remote Desktop**, entre outros.

Funciona 100% no navegador (sem necessidade de servidor) e utiliza o `LocalStorage` do navegador como banco de dados local, com opções de **importar e exportar planilhas Excel** para backup e compartilhamento.

👉 **[Experimente agora a versão online](https://rubenbruno89.github.io/painel-de-acessos-remotos/)**

---

## ✨ Funcionalidades

- ✅ **Cadastro completo**: Nome, Software (texto livre), ID de Acesso, Senha e Observação
- 📋 **Copiar com um clique**: Botões dedicados para copiar o ID e a Senha diretamente para a área de transferência
- 👁️ **Ocultar senhas**: Alternância para exibir ou mascarar senhas na visualização
- 📥 **Importar Excel**: Carregue uma planilha `.xlsx` existente para popular o painel
- 📤 **Exportar Excel**: Gere um backup atualizado em formato Excel a qualquer momento
- 📄 **Planilha de exemplo**: Baixe um modelo pronto para começar a usar imediatamente
- 💾 **Salvamento automático**: Os dados persistem no navegador mesmo após fechar a página
- 📱 **100% Responsivo**: Funciona perfeitamente em celulares, tablets e desktops
- 🔍 **Diagnóstico de armazenamento**: Aviso automático caso o navegador esteja bloqueando o salvamento (ex: Modo Anônimo)

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura da página |
| **Tailwind CSS** (via CDN) | Estilização responsiva e moderna |
| **JavaScript (Vanilla)** | Lógica da aplicação |
| **SheetJS (XLSX)** | Leitura e escrita de arquivos Excel |
| **Font Awesome** | Ícones da interface |
| **LocalStorage** | Persistência local dos dados |

---

## 🚀 Como Usar
### Opção 1: Versão Online (Recomendado)
Acesse diretamente pelo navegador:

🔗 **https://rubenbruno89.github.io/painel-de-acessos-remotos/**

### Opção 2: Rodar Localmente
1. Clone o repositório:
```bash
   git clone https://github.com/rubenbruno89/painel-de-acessos-remotos.git
```
2. Abra o arquivo `index.html` no seu navegador (Chrome, Edge, Firefox, Safari).
3. Pronto! O painel já está funcionando.

### Fluxo de Uso
1. **Primeiro acesso**: Clique em **"Baixar Exemplo"** para obter uma planilha modelo.
2. **Preencher manualmente**: Use o formulário no topo para adicionar acessos.
3. **Importar dados**: Se já tem uma planilha, clique em **"Importar Excel"**.
4. **Copiar credenciais**: Use os ícones 📋 ao lado do ID e da Senha.
5. **Fazer backup**: Clique periodicamente em **"Exportar Excel"** para salvar seus dados.

---

## 📋 Estrutura da Planilha Excel

Para que a importação funcione corretamente, sua planilha deve conter as seguintes colunas:

| Nome | Software | ID_Acesso | Senha | Observacao |
|------|----------|-----------|-------|------------|
| Servidor Financeiro | AnyDesk | 123 456 789 | senha123 | Acesso comercial |
| PC do João | HostDesk | 987 654 321 | abc@2024 | Monitor 2 desligado |

> 💡 **Dica**: Use o botão **"Baixar Exemplo"** para gerar automaticamente uma planilha modelo.

---

## ⚠️ Aviso de Segurança Importante

> 🔒 **Os dados são armazenados localmente no seu navegador** (LocalStorage) e **não são criptografados**.

- Qualquer pessoa com acesso ao seu navegador poderá visualizar as senhas.
- **Não use** este painel para credenciais críticas (bancos, servidores de produção, dados sensíveis).
- **Faça backup regularmente** exportando para Excel, pois limpar os dados do navegador apagará tudo.
- Para senhas de alta criticidade, utilize gerenciadores profissionais como **Bitwarden**, **1Password** ou **KeePass**.

---

## 🖼️ Capturas de Tela

<div align="center">  <img src="docs/screenshot-desktop.png" alt="Versão Desktop" width="800"/>
  <p><em>Interface no desktop com todos os dados visíveis</em></p>
</div>

<div align="center">
  <img src="docs/screenshot-mobile.png" alt="Versão Mobile" width="300"/>
  <p><em>Interface responsiva no celular</em></p>
</div>

> 📸 *Adicione imagens reais nas pastas `docs/` para exibir as capturas de tela.*

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commitar suas alterações (`git commit -m 'Adiciona NovaFeature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abrir um Pull Request

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido por **Ruben Bruno**

[![GitHub](https://img.shields.io/badge/GitHub-rubenbruno89-181717?style=flat&logo=github)](https://github.com/rubenbruno89)

---

<div align="center">
  <sub>Feito com ❤️ usando HTML, CSS e JavaScript puro.</sub>
  <br>
  <sub>⭐ Se este projeto foi útil, considere deixar uma estrela!</sub>
</div>
