## 🙋‍♂️ Autor

<div align="center">
  <img src="https://avatars.githubusercontent.com/ninomiquelino" width="100" height="100" style="border-radius: 50%">
  <br>
  <strong>Onivaldo Miquelino</strong>
  <br>
  <a href="https://github.com/ninomiquelino">@ninomiquelino</a>
</div>

---

# 🇧🇷 Consulta CNPJ - API ReceitaWS - Brasil

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC.svg)
![API](https://img.shields.io/badge/API-ReceitaWS-green.svg)
![License MIT](https://img.shields.io/badge/License-MIT-green)
![Status Stable](https://img.shields.io/badge/Status-Stable-success)
![Version 1.0.0](https://img.shields.io/badge/Version-1.0.0-blue)
![GitHub stars](https://img.shields.io/github/stars/NinoMiquelino/consulta-cnpj-api?style=social)
![GitHub forks](https://img.shields.io/github/forks/NinoMiquelino/consulta-cnpj-api?style=social)
![GitHub issues](https://img.shields.io/github/issues/NinoMiquelino/consulta-cnpj-api)

Uma aplicação web moderna e responsiva para consulta de dados de empresas brasileiras utilizando a API pública da ReceitaWS.

## ✨ Funcionalidades

- 🔍 **Consulta por CNPJ** - Busca completa de dados empresariais
- 🎨 **Interface Moderna** - Design responsivo com Tailwind CSS
- 📱 **Mobile First** - Otimizado para dispositivos móveis e desktop
- 🏷️ **Cards Organizados** - Visualização em seções distintas:
  - Dados básicos da empresa
  - Atividade principal
  - Atividades secundárias
  - Quadro societário
- 🟢 **Status Visual** - Destaque colorido para situação cadastral (Verde para ATIVA, Vermelho para outras)
- ⚡ **Performance** - Consulta rápida com tratamento de erros
- 🎯 **UX Melhorada** - Limpeza automática ao interagir com o campo

## 🚀 Como Usar

### Opção 1: Acesso Online
1. Acesse o projeto hospedado (se disponível)
2. Digite o CNPJ no campo de busca
3. Clique em "Consultar" ou pressione Enter

### Opção 2: Execução Local
1. Clone o repositório:
```bash
git clone https://github.com/NinoMiquelino/consulta-cnpj-app.git
```

1. Abra o arquivo index.html em um navegador moderno
2. Digite um CNPJ válido (apenas números) e clique em "Consultar"

📋 Exemplos de CNPJ para Teste

· 33.014.556/0001-96 - LOJAS AMERICANAS S.A.
· 60.701.190/0001-04 - ITAU UNIBANCO
· 00.000.000/0001-91 - BANCO DO BRASIL SA

🛠️ Tecnologias Utilizadas

· JavaScript ES6+ - Lógica da aplicação e consumo de API
· Tailwind CSS - Framework CSS para estilização responsiva
· HTML5 - Estrutura semântica
· ReceitaWS API - API pública para consulta de CNPJ
· JSONP - Contorno de políticas CORS

📁 Estrutura do Projeto

```
consulta-cnpj-app/
├── index.html          # Arquivo principal da aplicação
├── README.md           # Documentação do projeto
└── LICENSE            # Arquivo de Licença  da aplicação
```

🎨 Layout e Componentes

Seções da Aplicação

1. Header - Campo de busca e botão de consulta
2. Banner de Situação - Status visual da empresa (ATIVA/OUTRAS)
3. Dados Básicos - Informações fundamentais da empresa
4. Atividade Principal - CNAE principal da empresa
5. Atividades Secundárias - Lista de CNAEs secundários
6. Quadro Societário - Sócios e administradores

Design Responsivo

· Mobile: Layout em coluna única
· Tablet: Ajuste progressivo dos grids
· Desktop: Layout multi-coluna otimizado

🔧 Funcionalidades Técnicas

Tratamento de Dados

· Formatação automática de CNPJ (XX.XXX.XXX/XXXX-XX)
· Formatação de datas no padrão brasileiro
· Formatação de moeda (R$)
· Validação de campos obrigatórios

Gerenciamento de Estado

· Loading durante consultas
· Tratamento de erros da API
· Limpeza automática de consultas anteriores
· Feedback visual para o usuário

Integração com API

```javascript
// Exemplo de consulta
https://receitaws.com.br/v1/cnpj/33014556000196?callback=callback_123456789
```

⚠️ Limitações e Considerações

· A API da ReceitaWS possui limitações de rate limiting
· Dados dependem da atualização cadastral na Receita Federal
· Consultas podem falhar durante picos de uso
· Alguns CNPJs podem retornar dados incompletos

🐛 Solução de Problemas

Erro "Failed to fetch"

· Verifique a conexão com internet
· A API pode estar temporariamente indisponível
· Tente novamente após alguns segundos

Dados Incompletos

· Algumas empresas possuem informações limitadas na base pública
· Campos não informados serão marcados como "Não informado"

CNPJ Não Encontrado

· Verifique se o CNPJ foi digitado corretamente
· Confirme que o CNPJ existe na base da Receita Federal

🔗 Links Úteis

· [API ReceitaWS](https://receitaws.com.br/)
· [Tailwind CSS](https://tailwindcss.com/)
· [Documentação JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

---

## 🤝 Contribuições
Contribuições são sempre bem-vindas!  
Sinta-se à vontade para abrir uma [*issue*](https://github.com/NinoMiquelino/consulta-cnpj-app/issues) com sugestões ou enviar um [*pull request*](https://github.com/NinoMiquelino/consulta-cnpj-app/pulls) com melhorias.

---

## 💬 Contato
📧 [Entre em contato pelo LinkedIn](https://www.linkedin.com/in/onivaldomiquelino/)  
💻 Desenvolvido por **Onivaldo Miquelino**

---
