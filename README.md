# Fluxo-De-Projeto---Smart-You
Fluxograma do processo de projetos SmartYou
## Fluxo Geral de Projetos SmartYou

```mermaid
flowchart TD

A[Contrato Assinado<br/>Proposta aprovada] --> B[Projeto oficialmente aberto<br/>Cadastro Conta Azul + Trello]

B --> C[Coleta Inicial de Informações<br/>Status da obra<br/>Fotos, vídeos, projetos<br/>Cronograma]

C --> D[Projeto Executivo<br/>Checklist infraestrutura<br/>Plantas técnicas<br/>Lista de materiais<br/>Diagrama de rede<br/>Cronograma interno]

D --> E{Visita de Conferência}

E -->|Visita NÃO OK| D
E -->|Visita OK| F[Plano de Compras<br/>Prazos<br/>Marcas<br/>Fornecedores<br/>Lista de compra]

F --> G{Materiais disponíveis?}

G -->|Não| F
G -->|Sim| H[Separação de Materiais<br/>Conferência<br/>Almoxarifado<br/>Kit de instalação]

H --> I[Configuração com Luminotécnico<br/>Cenas e lógica<br/>Homologação técnica]

I --> J[Orientação para Operação<br/>Equipe de instalação<br/>Registro de dificuldades]

J --> K{Instalação}

K -->|Pendências| K
K -->|Sem pendências| L[Comissionamento in loco<br/>Testes finais<br/>Integrações<br/>Manual do cliente<br/>Vídeos]

L --> M[Entrega Final ao Cliente<br/>Demonstração<br/>Documentação<br/>Aceite formal]

M --> N[Fim do Projeto<br/>Encaminhado para pós-venda]
