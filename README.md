# Limpeza dos dados da *Peen World Table*.
---
Este repositório contém o conjunto de dados disponivél no *Peen World Table* referente ao Brasil. 

---

### 1. **Sobre o Banco de Dados:**

*[Peen World Table](https://www.rug.nl/ggdc/productivity/pwt/?lang=en)* é uma plataforma que disponibiliza dados como: níveis relativos de renda, produção, insumos e produtividade. Sua amostra atualmente cobre um conjuto de 182 países de 1950 a 2017. 

### 2. **Processo de organização e limpeza:**

Por se tratar de um banco de dados internacional, todas as variaveis estão em inglês. Assim, o processo de organização e limpeza consistiu em:

  - Traduzir as variaveis (colunas) de acordo com o documento disponível no [Guia do Usuário do PWT 9.1](https://www.rug.nl/ggdc/docs/pwt91_user_guide_to_data_files.pdf) e as informações adicionais do *site*; e,
  - Renomear as colunas, já traduzidas, retirando as siglas e adicionando os nomes completos de cada uma das variáveis.
  
**_Observação_**: As colunas com dados NA não foram retiradas. Caso o seu estudo precise omitir os dados NA, basta rodar o cógido:
  
  ```
  dados_brasil <- na.omit(dados_brasil)
  
  ``` 
 
### 3. **_Software_ utilizado:**
  - R.

### 4. **Andamento do processo:**

- **PIB real, níveis de emprego e população]:**

- [x] PIB real do lado da despesa em PPPs encadeadas (em US $ mil. 2011).
- [x] PIB real do lado da produção em PPPs encadeadas (em US $ mil. 2011).
- [x] População (em milhões).
- [x] Número de pessoas ocupadas (em milhões).
- [x] Média anual de horas trabalhadas por pessoas contratadas.
- [x] Índice de capital humano, baseado em anos de escolaridade e retornos à educação.



 
