# Meu Blog Pessoal com Flask & API npoint 🚀

Este é um projeto de blog dinâmico desenvolvido em Python utilizando o framework **Flask**. A aplicação consome dados de uma API externa criada no **npoint.io**, permitindo que os posts, imagens e informações do autor sejam carregados dinamicamente sem a necessidade de um banco de dados local.

Os posts do blog misturam minhas experiências profissionais em eletromecânica e automação industrial com minha jornada de estudos em desenvolvimento de software (Python, Java e SQL) e perspectivas do meu hobby, o skate.

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Flask** (Framework Web)
* **Requests** (Biblioteca para consumo de APIs HTTP)
* **npoint.io** (Servidor de hospedagem para dados JSON)
* **HTML5 / CSS3** (Templates para interface do usuário)

## 📌 Funcionalidades

* **Página Inicial (`/`):** Lista todos os posts recuperados dinamicamente da API externa.
* **Rota Dinâmica de Posts (`/post/<int:index>`):** Filtra e exibe o conteúdo completo de um post específico com base no seu ID único.
* **Páginas Institucionais:** Rotas dedicadas para informações sobre mim (`/about`) e contato (`/contact`).

## 🔧 Como Executar o Projeto Localmente

### Pré-requisitos
Certifique-se de ter o Python instalado em sua máquina. Você pode verificar rodando:
```bash
python --version