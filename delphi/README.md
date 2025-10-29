# 🧩 Teste Técnico – Delphi

## 🎯 Objetivo
O objetivo deste teste é avaliar seu domínio prático em **Delphi**, com foco em:

- **Orientação a Objetos**
- **Manipulação de Listas Genéricas**
- **Persistência de dados em arquivos texto**
- **Uso de componentes visuais**

---

## 🧱 Requisitos da Aplicação

### ⚙️ Funcionalidades obrigatórias
- Listar os clientes cadastrados.  
- Permitir o cadastro de novos clientes.  
- Permitir a edição de cadastros existentes.  
- Permitir a exclusão de cadastros.  
- Exibir os dados em uma **grid simples**.  
- Permitir a pesquisa de clientes por **ID** e/ou **Nome**.  
- A aplicação deve separar a extrutura visual, da regra de negocio e da manipulação do registro (Aplicar MVC)
- O documento deve ter uma validação para saber se é um documento valido

---
### 💡 Funcionaliades Extras
- Exportar o conteudo da listagem para CSV
- Input de pesquisa com coportamento dinamico (Sempre que você digitar a pesquisa ser feita com base no que já foi escrito)


### 💾 Persistência dos Dados
- Os dados devem ser armazenados em um **arquivo texto** (em vez de um banco de dados).  
- Todas as alterações (**inclusões, edições e exclusões**) devem refletir no arquivo texto, mantendo-o **sincronizado** com os dados exibidos na aplicação.  

---

### 👤 Estrutura do Cliente
Cada cliente deve conter as seguintes informações:

| Campo        | Tipo        | Descrição                   |
|---------------|-------------|------------------------------|
| **ID**        | Integer     | Identificador único          |
| **Nome**      | String(100) | Nome completo do cliente     |
| **E-mail**    | String(100) | Endereço de e-mail           |
| **Documento** | String(14)  | CPF ou CNPJ                  |

---

## 🚀 Entrega

1. Faça um **fork deste repositório** para a sua conta do GitHub.  
2. Desenvolva o projeto no seu fork, atendendo aos requisitos descritos acima.  
3. Após a conclusão, **abra uma Pull Request (PR)** para este repositório original.  
4. No espaço da PR, **descreva as decisões técnicas, medidas adotadas e soluções implementadas** durante o desenvolvimento.  

---

## 🧠 Dicas (opcional)
- Estruture o código de forma organizada, utilizando boas práticas de **OOP**.  
- Comente trechos relevantes do código, explicando suas escolhas.  
- Prefira componentes e estruturas nativas do Delphi, sempre que possível.  

---

✉️ **Boa sorte!**
