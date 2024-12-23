### Prompt Melhorado

Gere dados fictícios para preencher uma tabela com o seguinte cabeçalho:

**Cabeçalho da Tabela:**
- Data
- Tipo
- Categoria
- Descrição
- Valor
- Operação Bancária
- Status

**Instruções de Preenchimento:**
1. O campo **"Tipo"** deve alternar entre os valores: `"entrada"` e `"saída"`.
2. O campo **"Data"** deve conter datas válidas em formato `DD/MM/AAAA`, abrangendo um intervalo de pelo menos um mês.
3. O campo **"Categoria"** pode incluir valores como: `"Alimentação"`, `"Transporte"`, `"Educação"`, `"Saúde"`, `"Lazer"`, ou `"Outros"`.
4. O campo **"Descrição"** deve ser uma breve explicação relacionada à categoria.
5. O campo **"Valor"** deve conter valores numéricos em moeda, variando entre `R$10,00` e `R$1000,00`.
6. O campo **"Operação Bancária"** deve indicar `"TED"`, `"DOC"`, `"PIX"`, ou `"Transferência Interna"`.
7. O campo **"Status"** deve indicar: `"Concluído"`, `"Pendente"`, ou `"Cancelado"`.

**Exemplo de Dados Gerados:**

| Data       | Tipo    | Categoria     | Descrição            | Valor     | Operação Bancária  | Status       |
|------------|---------|---------------|----------------------|-----------|--------------------|--------------|
| 12/12/2024 | entrada | Alimentação   | Venda de produtos    | R$200,00  | PIX                | Concluído    |
| 13/12/2024 | saída   | Transporte    | Passagem de ônibus   | R$10,50   | Transferência Interna | Concluído |
| 14/12/2024 | entrada | Saúde         | Reembolso consulta   | R$500,00  | TED                | Pendente     |

Crie pelo menos **15 linhas** de dados que sigam as instruções acima.