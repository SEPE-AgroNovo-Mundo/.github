# SEPE-AgroNovo-Mundo

Documento de Requisitos – AgroNovo-Mundo
Plataforma de Comércio e Análise de Produtos Agropecuários

1. Introdução
O agronegócio brasileiro representa um dos setores mais relevantes da economia nacional, sendo responsável por grande parte do PIB, geração de empregos e exportações. Apesar de sua relevância, muitos produtores rurais ainda enfrentam dificuldades em acessar mercados competitivos, obter logística adequada e acompanhar informações de preço, qualidade e rastreabilidade de seus produtos.
O AgroNovo-Mundo é uma proposta de plataforma digital de comércio eletrônico especializada no setor agropecuário. Seu diferencial está na integração de funcionalidades de marketplace com sistemas de análise de mercado, promovendo transparência, inclusão e sustentabilidade.

2. Objetivos
2.1 Objetivo Geral
Desenvolver uma plataforma digital que conecte produtores, distribuidores e consumidores, permitindo compra, venda e análise de produtos agropecuários em ambiente seguro e sustentável.
2.2 Objetivos Específicos
Promover a inclusão digital de pequenos e médios produtores.


Criar um canal de comercialização direta, reduzindo intermediários.


Disponibilizar ferramentas de análise de preços e tendências de mercado.


Permitir rastreabilidade e certificações de produtos.


Integrar soluções logísticas, incluindo cálculo de frete e transporte rural.


Oferecer ambiente seguro para pagamentos e transações.


Incentivar práticas agrícolas sustentáveis e certificações reconhecidas.



3. Público-Alvo
Produtores Rurais: pequenos, médios e grandes produtores que desejam comercializar sua produção.


Distribuidores: cooperativas, atacadistas e empresas que compram em grande escala.


Consumidores Finais: indivíduos ou empresas interessados em adquirir produtos agropecuários diretamente da fonte.


Pesquisadores e Órgãos Públicos: interessados em dados analíticos para políticas públicas e pesquisas de mercado.



4. Justificativa
A inexistência de plataformas especializadas limita a competitividade de pequenos produtores e dificulta o acesso do consumidor a informações confiáveis. Além disso, a intermediação excessiva eleva preços e reduz margens de lucro no campo.
O AgroNovo-Mundo busca resolver esses problemas, oferecendo:
Aproximação direta entre produtores e consumidores.


Transparência nas negociações, com dados analíticos e reputação dos vendedores.


Eficiência logística, reduzindo perdas e otimizando transportes.


Base de dados robusta, útil para empresas, academia e governo.


Valorização da sustentabilidade, incentivando boas práticas agrícolas.



5. Metodologia
O desenvolvimento será dividido em fases:
Levantamento de requisitos – entrevistas e questionários com produtores e consumidores.


Modelagem do sistema – definição de arquitetura modular.


Protótipo (MVP) – funcionalidades básicas: cadastro, anúncios, compras.


Módulo de análise – gráficos, relatórios e comparativos de preços.


Módulo de reputação – avaliações e feedback de usuários.


Integração logística e pagamentos – cálculo de frete, rastreamento, gateways de pagamento.


Testes e validação – pilotos em regiões selecionadas.


Implantação final – versões web e mobile.



6. Requisitos
6.1 Requisitos de Negócio (RN)
RN01: Facilitar a comercialização digital de produtos agropecuários.


RN02: Ampliar a visibilidade de pequenos e médios produtores.


RN03: Oferecer informações confiáveis sobre qualidade, certificação e rastreabilidade.


RN04: Promover redução de intermediários e custos.


RN05: Incentivar a adoção de práticas agrícolas sustentáveis.


RN06: Fornecer dados analíticos estratégicos para o setor.


6.2 Requisitos Funcionais (RF)
RF01: Cadastro e autenticação de usuários.


RF02: Criação e gerenciamento de anúncios de produtos.


RF03: Implementação de carrinho de compras e checkout.


RF04: Intermediação de pagamentos via gateways seguros.


RF05: Sistema de reputação com avaliações e comentários.


RF06: Geração de gráficos de preços e relatórios de mercado.


RF07: Integração de cálculo de frete e rastreamento de pedidos.


RF08: Disponibilização de informações sobre certificações.


RF09: Suporte a múltiplos métodos de entrega (transportadoras, cooperativas, retiradas locais).


RF10: Notificações automáticas (status de pedidos, atualizações de preços, mensagens internas).


6.3 Requisitos Não Funcionais (RNF)
RNF01: Plataforma responsiva (web e mobile).


RNF02: Garantir disponibilidade mínima de 99,5%.


RNF03: Tempo de resposta inferior a 3 segundos em operações comuns.


RNF04: Armazenamento seguro de dados conforme LGPD.


RNF05: Interface intuitiva adaptada ao público rural.


RNF06: Escalabilidade para suportar picos sazonais de uso.


RNF07: Compatibilidade com múltiplos navegadores e sistemas operacionais.


RNF08: Logs de auditoria para monitoramento de transações.



7. Casos de Uso (exemplos)
UC01 – Cadastro de Produtor: o produtor cria perfil, insere dados pessoais e da propriedade.


UC02 – Publicar Produto: o produtor anuncia um lote, definindo preço, quantidade e certificações.


UC03 – Compra de Produto: o consumidor adiciona ao carrinho, escolhe forma de pagamento e confirma.


UC04 – Avaliação de Vendedor: após a compra, o consumidor avalia a experiência.


UC05 – Análise de Preços: usuário consulta gráficos históricos de determinado produto.


UC06 – Rastreabilidade: consumidor verifica origem e certificações do alimento adquirido.



8. Arquitetura Inicial
A plataforma seguirá arquitetura baseada em microserviços, garantindo escalabilidade e modularidade.
Frontend: React/Next.js (web) + React Native (mobile).


Backend:Python(Django)


Banco de Dados:Supabase..


Integração: APIs RESTful + suporte a GraphQL.


Segurança: autenticação via Python.



9. Resultados Esperados
Inclusão digital de produtores rurais.


Redução de custos e aumento de competitividade.


Transparência e confiança nas negociações.


Geração de dados estratégicos para políticas públicas.


Fomento à sustentabilidade e inovação no agronegócio.



10. Considerações Finais
O AgroNovo-Mundo é mais que um marketplace: é uma solução completa que une comércio eletrônico, inteligência de dados e incentivo à sustentabilidade. Sua implementação representa um avanço tecnológico no setor agropecuário, com impactos positivos para produtores, consumidores e sociedade.

