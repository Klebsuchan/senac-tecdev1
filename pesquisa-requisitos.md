# Requisitos Funcionais vs. Não Funcionais

Na engenharia de software, a diferença central entre esses dois conceitos se resume a **o que** o software faz versus **como** ele faz.

---

## 🎯 Requisitos Funcionais (O "Que")
Descrevem o comportamento, as regras de negócio e as ações práticas que o sistema deve executar. São as funcionalidades visíveis que o usuário final utiliza.

**Exemplos práticos (Aplicativo de Delivery de Cigarros/Tabacaria):**

1. **Validação Legal:** O sistema deve solicitar e aprovar a foto de um documento oficial provando que o usuário é maior de 18 anos antes de liberar o acesso ao catálogo.
2. **Gestão de Pedidos:** O cliente deve conseguir adicionar diferentes maços, caixas, sedas e isqueiros ao carrinho, calculando o frete automaticamente com base na distância da tabacaria.
3. **Rastreamento:** O aplicativo deve notificar o usuário em tempo real assim que o entregador retirar o pacote no estabelecimento parceiro.

---

## ⚙️ Requisitos Não Funcionais (O "Como")
Definem os critérios de qualidade, as restrições e a arquitetura por trás da aplicação. Envolvem fatores como segurança, desempenho, escalabilidade e usabilidade (não são funcionalidades diretas, mas atributos de qualidade do sistema).

**Exemplos práticos (Aplicativo de Delivery de Cigarros/Tabacaria):**

1. **Segurança (Privacidade):** As fotos dos documentos de identidade dos usuários e os dados financeiros devem ser armazenados no banco de dados com criptografia avançada de ponta a ponta.
2. **Desempenho (Performance):** A listagem das tabacarias e do estoque de produtos próximos deve carregar na interface do usuário em, no máximo, 2 segundos.
3. **Disponibilidade (Confiabilidade):** A infraestrutura deve suportar altos picos de tráfego durante as madrugadas de sexta e sábado, garantindo um uptime (tempo de atividade) de 99,9% sem quedas no servidor.
