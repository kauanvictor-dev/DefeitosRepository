# Plano de Teste — [SystemFacil] v[0.1]

> **Como usar este modelo:** copie este arquivo para a pasta `entregas/`, com o nome `PLANO-DE-TESTE-AgendaFacil.md`, e substitua tudo o que está entre colchetes. Os quadros "Exemplo" mostram o nível de detalhe esperado, usando **outro sistema** (uma floricultura online). Apague os exemplos quando terminar.

---

## 1. Identificação

| Campo | Preenchimento |
| --- | --- |
| Identificador do plano | [PT-AAAA-091] |
| Versão do plano | [1.0] |
| Sistema e versão testada | [Agenda Fácil / 1.0 ] |
| Documento de referência | [Documento de requisitos e versão] |
| Autor | [Kauan victor] |
| Data | [03/11/2007] |

**Histórico de versões**

| Versão | Data | Autor | O que mudou |
| --- | --- | --- | --- |
| 1.0 | [03/11] | [Kauan] | Primeira versão testada |

## 2. Introdução e objetivo

[Em 3 a 5 linhas: o que é o sistema, para quem é, e o que este ciclo de testes precisa responder.]

>**Sistema AgendaFacil:** Essa Operação define os testes da versão 1.0 do Site AgendaFácil um Site desenvolvido para agendar seus cortes de cabelo 100% Online e Simples de organizar suas consultas e agendamento de corte de cabelo. objetivo dessa operação é a Inauguração da Loja fisica. E conseguir marcar seus cortes de cabelo dentro da sua propria casa.


## 3. Itens de teste

[Quais partes do sistema serão testadas: aplicativos, versões, módulos, plataformas.]

## 4. Funcionalidades que serão testadas

| Regra ou requisito | Funcionalidade | Tipo de teste | Técnica | Prioridade |
| --- | --- | --- | --- | --- |
| [RN09] | [Alerta de Lembrete] | [plataformas] | [2 Alertas de Agendamento] | [Média] |
| | | | | |

**Prioridade:** Alta = impede o uso principal ou envolve dinheiro ou dados pessoais. Média = afeta uma regra importante, com contorno. Baixa = conforto ou aparência.

## 5. Funcionalidades que não serão testadas

| Funcionalidade | Motivo |
| --- | --- |
| [ RN09 - Lembre WhatsApp ] | [ Fora do escopo da versão / Tela de Consulta / risco Médio] |

## 6. Abordagem

- **Estratégia:** [RN09 - preventiva, Evitar que o Usuário se esqueça a Consulta marcada no sistema]
- **Níveis de teste:** [RN09 - unitário e aceitação: quais e quem executa]
- **Tipos de teste:** [funcional E usabilidade ]
- **Técnicas:** [partição de equivalência]
- **Manual ou automatizado:** [A automatização será na parte do envio do Alerta/Mensagem para o usuário e o Manual será a parte de selecionar a quem enviar, digitalização do Email do usuário e o que está dentro da mensagem precisa também ser escrita, O sistema é feito para facilitar a parte das demandas da Empresa de Cortes em diminuir a sobrecarga de usuários presencialmente]

## 7. Critérios de aprovação e falha

- **Um caso de teste passa quando:** [ Todos os Critérios de aceitação enviados para a operação forem preenchidos com perfeição]
- **Critério de saída (o ciclo termina e o sistema pode ser lançado quando):** [ Os dados do usuário forem confirmados perfeitamente, todas as regras de negócios forem aprovadas e nenhuma falha na operação for detectada ( De risco alto )]

> **Exemplo (floricultura):** O ciclo termina quando 100% dos casos de prioridade Alta forem executados, pelo menos 95% de todos os casos tiverem passado e nenhum defeito crítico ou alto estiver aberto.

## 8. Critérios de suspensão e retomada

- **Os testes são suspensos quando:** [ Alterações drásticas no escopo ou design do projeto durante a fase de execução de testes.]
- **Os testes são retomados quando:** [ Quando tudo for reescrito e confirmado pela Equipe]

> **Exemplo (floricultura):** Suspender se o ambiente de homologação ficar fora do ar por mais de 1 hora, ou se o smoke test falhar numa nova versão. Retomar quando o ambiente voltar e o smoke test passar.

## 9. Entregáveis de teste

| Entregável | Quando é entregue | Responsável |
| --- | --- | --- |
| Plano de teste | [Antes do início] | [Nome] |
| Especificação dos casos de teste | Inicialmente após o plano de teste for iniciado | Equipe QA |
| Registro de execução (log) | Após o fim dos testes Especificos  | Kauan |
| Relatórios de defeito | A anotação vem quando a equipe de Testes analisa o Registro de execução | Equipe QA |
| Relatório final de teste | A conclusão de que o sistema está 100% testado ( No fim ) | Equipe QA |

## 10. Ambiente de teste

| Item | Detalhe |
| --- | --- |
|  Android - Versão 12| [Motorola Edge 13] |
| Navegadores | [Desktop e IOS - Microsoft Edge] |
| Ambiente | [ Homologação ] 
| Dados de teste | [extraídos de banco de dados fictício] |
| Ferramentas | [Google Chrome e Vscode] |

## 11. Responsabilidades e cronograma

| Atividade | Responsável | Início | Fim |
| --- | --- | --- | --- |
| [Preparar ambiente e dados] | Kauan | 01 |INÍCIO |
| [Executar testes de prioridade Alta] |Kauan| 02 | INÍCIO/MEIO |
| [Reteste e regressão] |Kauan |  03 | MEIO/FIM |
| [Relatório final] |Kauan | 04 | FINAL |

## 12. Riscos e contingências

| Risco | Probabilidade | Impacto | O que fazer se acontecer |
| --- | --- | --- | --- |
| [o parceiro de entregas não libera o ambiente de testes.] | [Alta] | [Médio] | [Plano de Reorganização] |

> **Exemplo (floricultura):** Risco: o parceiro de entregas não libera o ambiente de testes. Probabilidade: média. Impacto: alto. Contingência: testar a integração com respostas simuladas e registrar o risco no relatório final.

## 13. Aprovações

| Papel | Nome | Data |
| --- | --- | --- |
| Analista de testes | Kauan victor | 04/11/2026 |
| Responsável pelo produto | AgenciaFacil | Data do Pedido: 01/21/2026 |
