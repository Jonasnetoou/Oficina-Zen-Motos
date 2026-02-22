# Oficina-Zen-Motos
Diferente de soluções genéricas, este sistema foi desenvolvido e refinado com feedback direto do cliente. Cada funcionalidade, do fluxo do carrinho à lógica de vistorias, atende a uma operação real de alta performance. É uma solução única no mercado, onde o rigor da Engenharia de Computação encontra a praticidade do dia a dia da oficina.

Zen Motos - ERP Pro V44.0 (Versão Final)
💎 O ápice da Gestão de Oficinas e Estética Automotiva
O Zen Motos é uma solução completa de gestão empresarial desenvolvida sob demanda para o setor de motociclismo, unindo automação financeira, CRM avançado e controle de inventário em uma interface Dark Mode otimizada para produtividade extrema.

Este projeto representa a evolução máxima do "MOTOR JONAO", aplicando conceitos de Arquitetura Modular onde cada componente do sistema opera de forma independente, mas totalmente sincronizada através de uma camada de persistência em SQLite de alto desempenho.

🏗️ Arquitetura de Engenharia e Stack Técnica
O projeto foi construído com foco em Rigor Técnico e Estabilidade, utilizando uma stack moderna e resiliente:

Linguagem Core: Python 3.x.

Interface UI/UX: CustomTkinter para uma experiência nativa, escura e focada em touch-points.

Engine de Dados: SQLite3 com rotinas de auto-reparo e versionamento de schema (V45/V46).

Relatórios Profissionais: ReportLab para geração de PDFs dinâmicos com suporte a imagens e tabelas complexas.

Análise de Dados: Matplotlib para geração de gráficos de faturamento e mix de vendas.

Segurança: Multithreading para processos de backup em segundo plano sem impacto na UI.

🚀 Funcionalidades de Elite
1. Módulo de Atendimento e Vendas (atendimento.py)
Transforma o caos do balcão em um processo linear e rápido:

Carrinho Dinâmico: Gerenciamento de itens em tempo real com suporte a quantidades fracionadas (ideal para serviços/peças a granel).

Documentação Inteligente: Geração instantânea de Ordens de Serviço e Orçamentos com logo da empresa, dados do cliente, veículo e parecer técnico.

Integração Social: Botão de exportação direta para WhatsApp, enviando o orçamento formatado com um clique.

2. CRM e Gestão de Clientes (clientes.py)
Uma base de dados viva que entende o seu cliente:

Busca por CPF/Nome: Filtros instantâneos para localização de registros.

Integração com API ViaCEP: Cadastro de endereços automatizado a partir do CEP, reduzindo erros humanos.

Fidelização: Sistema de alerta para Aniversariantes do Dia, permitindo ações de marketing personalizadas.

3. Gestão de Frota e Vistoria (veiculos.py)
O prontuário completo da máquina:

Galeria de Fotos: Sistema de vistoria que permite anexar múltiplas fotos do veículo para segurança jurídica e acompanhamento de serviços.

Vínculo Híbrido: Capacidade de associar veículos a clientes cadastrados ou realizar registros avulsos de forma manual.

4. Inteligência Financeira e Dashboard (financeiro.py)
A cabine de comando da empresa:

KPIs em Tempo Real: Visualização de faturamento diário, contas a pagar e fluxo de motos no pátio.

Contas a Pagar Avançado: Controle de pagamentos com lógica de juros e descontos automáticos.

Estoque Preditivo: Alertas visuais para produtos que atingiram o estoque mínimo, garantindo que a oficina nunca pare por falta de peça.

🛡️ Protocolo de Segurança e Robustez
Seguindo as diretrizes do PROTOCOLO JOVEM PROGRAMADOR, o Zen Motos implementa:

Backup Automático (Dual-Layer): O sistema realiza cópias de segurança a cada 30 minutos, tanto localmente quanto em nuvem (Google Drive), operando sob a chave backup_auto_controle_do_motoca.

Auto-Reparo de Banco de Dados: Scripts integrados (reparar_banco.py) verificam a integridade das colunas e tabelas a cada inicialização, executando migrações automáticas se necessário.

UX Consistency: Máscaras financeiras, máscaras de CPF/Celular e capitalização automática (Title Case) em todos os campos, mantendo a base de dados padronizada e limpa.

📁 Estrutura Modular de Arquivos
Plaintext
/ZenMotos_ERP
├── main.py             # Orquestrador principal e Menu Lateral
├── atendimento.py      # Core de Vendas, Carrinho e PDF
├── clientes.py         # CRM e Integração com API CEP
├── veiculos.py         # Gestão de Frota e Galeria de Imagens
├── produtos.py         # Inventário e Controle de Margem
├── financeiro.py       # Dashboards e Contas a Pagar
├── database.py         # Camada de abstração do SQLite
├── utils.py            # Threads de Backup e Funções de Sistema
├── reparar_banco.py    # Ferramenta de manutenção e migração
└── atualizar_v45/46.py # Versionamento de schema do banco
🌟 Diferencial Competitivo
O Zen Motos não é apenas um software de gestão; é o resultado de anos de experiência no "trecho" como motoboy, traduzidos em linhas de código que entendem a dor do proprietário de oficina. Cada botão foi pensado para ser acessado com luvas ou mãos sujas (Touch UX), e cada relatório foi desenhado para transmitir o máximo de profissionalismo ao cliente final.

Este projeto é a prova de que o rigor técnico e a paixão pelo que se faz podem transformar uma necessidade de trabalho em uma ferramenta de engenharia de software impecável.

Status do Projeto: Finalizado / Estável ✅
Desenvolvedor: Jonas (Colaborador Técnico GSX 650RR)






