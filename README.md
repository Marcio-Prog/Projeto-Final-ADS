# Documentação Projeto Final ADS_Senac 2025/2
# Fideliza – Sistema Web de Gerenciamento de Pontos e Descontos

##  Resumo do Projeto

O Fideliza é um sistema web simples e eficiente voltado a pequenos comércios e farmácias que desejam implementar um programa de fidelidade com baixo custo. O sistema permite cadastrar clientes, registrar compras, acumular e resgatar pontos ou descontos, além de aplicar descontos personalizados.

##  Problema

A maioria dos pequenos estabelecimentos não possui ferramentas digitais acessíveis, simples e baratas para gerenciar programas de fidelidade, dificultando o relacionamento com seus clientes e a competitividade frente às grandes redes.

##  Objetivo

### Objetivo Geral
Desenvolver um sistema de fidelização de clientes fácil de usar, acessível e funcional para pequenos comércios e farmácias.

### Objetivos Específicos
- Cadastro de clientes  
- Registro de compras com geração de pontos  
- Resgate de pontos, descontos ou cash back  
- Painel administrativo com histórico de clientes  
- Base para integração com futuras soluções  

##  Stack Tecnológico

- **Frontend:** CSS Tailwind
- **Backend:** Python 
- **Banco de Dados:** SQLite 
- **Hospedagem:** AWS  

##  Fluxo Básico

1. Comerciante faz login  
2. Cadastra cliente  
3. Registra compra  
4. Sistema calcula pontos  
5. Cliente resgata pontos com desconto
6. O administrador visualiza histórico e gera relatórios simples. 

##  Arquitetura e Artefatos

- **MVC (Model-View-Controller)**
  
  Fluxo MVC resumido para o Fideliza

1) Usuário acessa /registrar-compra
→ Controller recebe
→ Valida
→ Chama Model para gravar compra e calcular pontos
→ Model retorna resultado
→ Controller envia para a View “Compra registrada com sucesso”

2) Comerciante acessa /clientes
→ Controller busca lista no Model
→ Envia para a View formatar e exibir
<img width="1536" height="1024" alt="MVC" src="https://github.com/user-attachments/assets/c8d1aba3-9774-473a-ae69-61d0d09f602e" />

- **Business Model Canvas**
 <img width="2245" height="1587" alt="CANVAS MVP" src="https://github.com/user-attachments/assets/eed35c41-3ad1-4e33-ab7a-d9c80edd6dde" />
 
- **Personas**
  
Personas 
1) João — Proprietário de Farmácia (45 anos)

Perfil: Dono de pequena farmácia de bairro.

Necessidades: Fidelizar clientes recorrentes, controlar promoções simples, ter relatório mensal de uso.

Técnica: Uso básico de computador e smartphone.

Objetivo com o sistema: Reduzir perda de clientes para grandes redes.

2) Maria — Gerente de Loja de Roupas (33 anos)

Perfil: Gerente operacional, responsável por vendas e equipe.

Necessidades: Acelerar checkout, oferecer recompensas por ticket médio mais alto, consultar histórico por cliente.

Técnica: Confortável com ferramentas web.

Objetivo com o sistema: Aumentar ticket médio e retenção.

3) Carlos — Cliente Fiel (28 anos)

Perfil: Comprador frequente, usa smartphone diariamente.

Necessidades: Ver saldo de pontos, resgatar com facilidade e ser notificado de ofertas.

Objetivo com o sistema: Receber descontos/sobres e acumular pontos sem burocracia.

4) Ana Paula — Proprietária de Salão de Beleza (38 anos)

Perfil: Dona de um salão pequeno com atendimento personalizado.

Necessidades: Fidelizar clientes que fazem serviços recorrentes (corte, escova, manicure), oferecer bônus por frequência e acompanhar o retorno das clientes.

Técnica: Usa bem redes sociais e ferramentas simples no celular.

Objetivo com o sistema: Aumentar a frequência mensal das clientes e criar promoções específicas.

5) Roberto — Dono de Lanchonete (47 anos)

Perfil: Proprietário de uma lanchonete movimentada em uma avenida.

Necessidades: Recompensar clientes diários, controlar cupons de desconto e evitar perda de clientes para concorrentes próximos.

Técnica: Conhecimento intermediário de informática; utiliza computador para pedidos e fechamento diário.

Objetivo com o sistema: Aumentar vendas durante horários de menor movimento e estimular fidelidade.

6) Fernanda — Cliente Esporádica (31 anos)

Perfil: Costuma comprar ocasionalmente, mas gosta de promoções.

Necessidades: Ser avisada quando há promoções, visualizar benefícios que realmente valem a pena e ter clareza nos resgates.

Técnica: Usa smartphone diariamente, mas prefere interfaces simples.

Objetivo com o sistema: Aproveitar oportunidades e economizar quando for conveniente.

7) Diego — Atendente de Loja (26 anos)

Perfil: Funcionário responsável pelo atendimento direto no caixa.

Necessidades: Sistema rápido, fácil de usar durante o atendimento e que permita cadastrar novos clientes sem complicação.

Técnica: Experiência moderada com ferramentas de loja e PDV.

Objetivo com o sistema: Agilizar atendimento e facilitar adesão dos clientes ao programa.

8) Sônia — Proprietária de Papelaria (54 anos)

Perfil: Dona de uma papelaria tradicional no bairro.

Necessidades: Criar fidelização para períodos fortes (volta às aulas) e manter clientes durante meses de baixa demanda.

Técnica: Uso básico de computador; prefere telas simples e diretas.

Objetivo com o sistema: Aumentar retorno dos clientes e incentivar compras ao longo do ano inteiro.

- **Backlog e histórias de usuário**
    
 Backlog
- Registrar cliente
- Registrar compra
- Consultar pontos
- Resgatar recompensas
- Gerenciar estabelecimentos
- Emitir relatórios

 Histórias de Usuário
1. Como cliente, quero consultar meus pontos para saber minhas recompensas.
2. Como atendente, quero registrar compras rapidamente para agilizar o atendimento.
3. Como administrador, quero emitir relatórios para acompanhar desempenho.
   
- **Protótipos (Wireframes)**  
- **Diagrama ER**  
<img width="1002" height="833" alt="diagrama" src="https://github.com/user-attachments/assets/a98f2cee-657b-49da-a9e9-4f3b58098b8c" />

##  Validação

Validação por meio de entrevistas e testes com pelo menos 5 comerciantes locais, baseando-se na norma ISO 9241-11. Serão analisados aspectos como usabilidade, eficiência e satisfação.

##  Futuras Expansões

- Aplicativo mobile  
- Integração com WhatsApp  
- Relatórios analíticos  
- Gamificação  
- Integração com PDV/ERP  

##  Referências

- Kotler & Keller. *Administração de Marketing*, 14ª Ed.  
- Sebrae. *Pesquisa sobre uso de ferramentas digitais em pequenos negócios* (2022)  
- Wazlawick, R. *Metodologia de pesquisa para ciência da computação*  
- [Tailwind CSS](https://tailwindcss.com/) – Framework CSS utilitário para estilização rápida e responsiva.
- [AWS Services](https://aws.amazon.com/) – Plataforma de nuvem para hospedagem, incluindo EC2 (computação), S3 (armazenamento), RDS (banco de dados) e Lambda (serverless).
- [FastAPI](https://fastapi.tiangolo.com/) – Framework moderno e rápido para construção de APIs com Python, baseado em Starlette e Pydantic.
- [SQLite](https://www.sqlite.org/) – Sistema de gerenciamento de banco de dados relacional leve e incorporado, usado para armazenamento local eficiente.


