# Social Insights 📊

Dashboard de análise e interpretação de métricas de redes sociais.

## Sobre o projeto

Projeto acadêmico de desenvolvimento back-end que busca centralizar
métricas de publicações do Instagram e Facebook, comparar resultados
e gerar insights descritivos para apoiar o planejamento de comunicação.

O Diário Gaúcho será utilizado como estudo de caso, com dados
sintéticos ou devidamente autorizados.

## Status

🚧 Em planejamento. As funcionalidades abaixo ainda serão implementadas.

## Objetivo

Transformar dados de redes sociais em informações claras sobre
o desempenho de publicações, temas e formatos.

## Funcionalidades previstas

- Importação de métricas por arquivo CSV.
- Validação de colunas, campos e publicações duplicadas.
- Armazenamento em banco de dados.
- Filtros por plataforma, período, tema e formato.
- Indicadores de alcance, visualizações e interações.
- Gráficos de evolução e ranking de publicações.
- Comparação entre meses e médias por publicação.
- Geração de insights com regras transparentes.
- Exportação simples de relatório.

## Tecnologias planejadas

| Tecnologia | Finalidade |
|---|---|
| Python | Desenvolvimento e processamento dos dados |
| FastAPI | API back-end |
| Pandas | Tratamento e análise dos dados |
| SQLite | Banco de dados do protótipo |
| Streamlit | Interface do dashboard |
| Plotly | Gráficos interativos |
| Git e GitHub | Versionamento do projeto |

IA generativa poderá ser adicionada futuramente para redigir
resumos a partir dos indicadores calculados.

## Funcionamento previsto

1. O usuário importa um arquivo CSV.
2. O back-end valida e padroniza os dados.
3. As publicações são armazenadas no banco.
4. O sistema calcula indicadores e compara períodos.
5. Regras identificam padrões de desempenho.
6. O dashboard apresenta gráficos, destaques e insights.

## Dados previstos

Cada publicação poderá conter:

- Identificador, plataforma e data.
- Legenda, tema e formato.
- Alcance e visualizações.
- Curtidas, comentários, compartilhamentos e salvamentos.
- URL da publicação, quando disponível.

Métricas ausentes serão mantidas como nulas, sem substituição
automática por zero. Taxas serão calculadas apenas quando
os denominadores necessários estiverem disponíveis e forem válidos.

## Estrutura planejada

```text
social-insights-dashboard/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── exemplo_sintetico.csv
├── backend/
│   ├── main.py
│   └── analytics.py
├── dashboard/
│   └── app.py
└── tests/
```

## Etapas de desenvolvimento

- [ ] Definir indicadores e o modelo do CSV.
- [ ] Criar dados sintéticos para demonstração.
- [ ] Implementar importação e validação.
- [ ] Configurar o banco de dados.
- [ ] Desenvolver cálculos e endpoints da API.
- [ ] Construir o dashboard.
- [ ] Implementar pelo menos três insights rastreáveis.
- [ ] Adicionar exportação de relatório.
- [ ] Testar os resultados e documentar a execução.

## Execução

As instruções de instalação e execução serão adicionadas
quando a primeira versão funcional estiver disponível.

## Cuidados metodológicos

Os insights serão descritivos. Uma associação entre tema,
formato e desempenho não comprova uma relação de causa e efeito.

Comparações considerarão o volume de publicações, a média
por post e as diferenças entre métricas das plataformas.

Serão utilizados somente dados sintéticos, públicos ou autorizados.
Credenciais, tokens e informações internas não serão publicados.

## Evoluções futuras

- Integração com APIs oficiais, mediante autorização.
- Classificação automática de temas.
- Alertas de desempenho atípico.
- Análise de comentários.
- Resumos com IA generativa.
- Autenticação e perfis de acesso.