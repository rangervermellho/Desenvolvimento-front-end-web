#  ONG Esperança Viva

Sistema web desenvolvido para gerenciar o cadastro de voluntários, exibir projetos sociais e promover ações comunitárias da ONG **Esperança Viva**.  
O projeto foi construído com foco em **Single Page Application (SPA)**, manipulação do **DOM**, **validação de formulários** e **armazenamento local** de dados (LocalStorage).

---

##  Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Instalação e Execução](#instalação-e-execução)
- [Como Contribuir](#como-contribuir)
- [Histórico de Versionamento](#histórico-de-versionamento)
- [Licença](#licença)
- [Créditos](#créditos)

---

##  Sobre o Projeto

O sistema foi desenvolvido com o objetivo de **digitalizar o processo de cadastro de voluntários** e **exibir os projetos da ONG** de forma interativa, utilizando conceitos modernos de **SPA (Single Page Application)** com **JavaScript puro**.

Além disso, o site conta com:
- Animações suaves e interativas;
- Validação de consistência de dados;
- Layout responsivo;
- Armazenamento de cadastros em `LocalStorage`;
- Interface amigável e intuitiva.

---

##  Funcionalidades

 Menu mobile com alternância dinâmica;  
 Scroll suave entre seções;  
 Sistema de cadastro de voluntários;  
 Validação de campos obrigatórios com aviso ao usuário;  
 Exibição de voluntários cadastrados em tabela;  
 Máscara automática de telefone;  
 Animações com base no scroll (efeito de entrada);  
 Layout responsivo e moderno.

---

##  Tecnologias Utilizadas

| Tipo | Ferramenta |
|------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript (DOM Manipulation) |
| **Armazenamento** | LocalStorage |
| **Controle de versão** | Git & GitHub |
| **Design e UI** | Responsividade, animações em CSS e JS |

---

##  Estrutura de Pastas

```
ong-esperanca-viva/
│
├── index.html
├── cadastro.html
├── projetos.html
│
├── /css/
│   ├── style.min.css 
│
├── /js/
│   ├── script.js
│
├── /img/
│   ├── aularef.png
│   ├── vol.png
│
├── /docs/
│   ├── Prestacao_de_contas_2024.pdf
│   ├── relatorio_anual_2024.pdf
│
└── README.md
```

---

##  Instalação e Execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seuusuario/ong-esperanca-viva.git
   ```

2. **Acesse a pasta do projeto**
   ```bash
   cd ong-esperanca-viva
   ```

3. **Abra o arquivo `index.html` no navegador**
   > Nenhuma dependência externa é necessária. O projeto roda localmente com HTML + JS puro.

---

##  Como Contribuir

1. Faça um fork do projeto  
2. Crie uma branch com a sua feature  
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações  
   ```bash
   git commit -m "Adiciona nova funcionalidade X"
   ```
4. Envie para o seu repositório  
   ```bash
   git push origin minha-feature
   ```
5. Abra um **Pull Request** neste repositório principal

> Cada PR deve referenciar uma **issue** (ex: “Resolve #5”) e conter descrição das alterações.

---

##  Histórico de Versionamento

- **v1.0.0** – Estrutura inicial do projeto, layout responsivo e validação de formulário  
- **v1.1.0** – Implementação de animações, máscara de telefone e scroll suave  
- **v1.2.0** – Ajustes de SPA e melhorias de UX/UI  

---

##  Licença

Este projeto está licenciado sob a licença **MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

##  Créditos

Desenvolvido por **Eduardo Neri** ONG Esperança Viva – Promovendo solidariedade, amor e esperança.

---

### 📎 Exemplo de Issue
> **Título:** Implementar validação no formulário de cadastro  
> **Descrição:** Verificar consistência dos campos “nome” e “email” e exibir mensagem de erro.  
> **Status:** Concluído   
