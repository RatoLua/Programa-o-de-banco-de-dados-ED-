# Wallet DB (BD_ED) 🚀
Sistema em SQL Server para gestão de carteiras multi-moedas e conversão de ativos.

### 📌 Principais Recursos
- Modelo Relacional: Cadastro de clientes, corretoras, moedas e saldos.
- Conversão de Moedas: Função (UDF) para cálculo de câmbio entre ativos.
- Visões Consolidadas: View para consulta rápida de saldos detalhados.
- Performance: Índices otimizados para busca por nomes e códigos.

### 🛠️ Estrutura (Schema WALLET_BD)
- CLIENTE & CORRETORA: Dados cadastrais.
- MOEDA & PARES_MOEDAS: Definição de ativos e taxas.
- CARTEIRA & ITEM_CARTEIRA: Localização e quantidade de ativos.
