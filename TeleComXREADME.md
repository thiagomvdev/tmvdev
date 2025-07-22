Relatorio Final

Projeto Telecom X - Análise de Churn (Evasão de Clientes)

Descrição
Este projeto objetiva analisar o índice de evasão de clientes (churn) da empresa Telecom X, uma operadora de telecomunicações.
Usando padrões e técnicas de Ciência de Dados, além do processo de ETL (Extração, Transformação e Carga), a análise busca
identificar padrões e fatores que influenciam a saída dos clientes, auxiliando na criação de modelos preditivos para redução da evasão.


# CONCLUSÕES E INSIGHTS

Cancelamento por Gênero
Observou-se uma leve predominância de cancelamentos entre mulheres, sugerindo que esse público pode ter expectativas específicas não totalmente atendidas pelos serviços atuais.

Faixa Etária e Cancelamento
Clientes com mais de 65 anos apresentaram maior tendência ao cancelamento, o que pode estar relacionado a dificuldades com tecnologia, atendimento ou custo dos planos.

Tempo de Contrato, Gasto Mensal e Cancelamento
A maior vulnerabilidade de churn ocorre entre clientes com menos de 30 meses de contrato e faturas mensais superiores a R$ 60.
Clientes mais antigos demonstram maior estabilidade, mesmo com gastos totais mais altos.

Formas de Pagamento e Risco de Cancelamento
Pagamentos via Cheque Eletrônico concentram os maiores índices de cancelamento, indicando menor conveniência percebida nesse método.
Cartão de crédito e débito automático apresentam maior retenção, reforçando a preferência por soluções práticas e automatizadas.

Tipo de Contrato e Retenção
Contratos mensais são mais suscetíveis a cancelamentos, reforçando que a flexibilidade vem acompanhada de maior rotatividade.
Planos de longo prazo (anual ou bianual) apresentaram performance mais positiva em retenção, mesmo considerando um volume absoluto menor de clientes.

Tipo de Internet e Percepção de Valor
Clientes de Fibra Óptica mostraram maior taxa de churn, o que pode indicar desalinhamento entre preço cobrado e qualidade percebida.
DSL e clientes sem serviço de internet apresentaram menor propensão ao cancelamento, demonstrando perfis de uso mais conservadores.

_________________________________________________________
_________________________________________________________
_________________________________________________________

RECOMENDAÇÕES
1. Programa de Retenção para Novos Clientes
Desenvolver ofertas específicas para os primeiros meses de contrato, combinando descontos e benefícios extras, priorizando clientes com gasto mensal mais elevado.

2. Reforço no Pacote de Valor da Fibra Óptica
Ampliar o pacote de benefícios associados à internet Fibra, incluindo serviços agregados como streaming, suporte técnico premium ou armazenamento em nuvem.

3. Otimização dos Meios de Pagamento
Ativar campanhas focadas em migrar clientes para pagamento por cartão ou débito automático, oferecendo pequenas vantagens financeiras para estimular essa troca.

4. Ações Específicas por Perfil de Cliente
Criar iniciativas direcionadas para públicos mais sensíveis, como idosos e mulheres, com comunicação personalizada e suporte mais acessível.

_________________________________________________________
_________________________________________________________
_________________________________________________________

⭐Dicionario

Dicionário de Variáveis

customerID: Número de identificação único de cada cliente.
Churn: Indica se o cliente deixou (cancelou) ou não a empresa.
gender: Gênero do cliente (masculino ou feminino).
SeniorCitizen: Informa se o cliente possui 65 anos ou mais.
Partner: Indica se o cliente possui ou não um parceiro(a).
Dependents: Informa se o cliente possui dependentes.
tenure: Meses de contrato do cliente.
PhoneService: Assinatura de serviço telefônico.
MultipleLines: Assinatura de mais de uma linha de telefone.
InternetService: Assinatura de um provedor de internet.
OnlineSecurity: Assinatura adicional de segurança online.
OnlineBackup: Assinatura adicional de backup online.
DeviceProtection: Assinatura adicional de proteção no dispositivo.
TechSupport: Assinatura adicional de suporte técnico (menos tempo de espera).
StreamingTV: Assinatura de TV a cabo.
StreamingMovies: Assinatura de streaming de filmes.
Contract: Tipo de contrato.
PaperlessBilling: Indica se o cliente prefere receber a fatura online.
PaymentMethod: Forma de pagamento.
Charges.Monthly: Total dos serviços contratados pelo cliente por mês.
Charges.Total: Total gasto pelo cliente até o momento.

