# Digital-Investigation
Este projeto é um repositório de conhecimento estruturado sobre forense digital, OSINT e metodologias de investigação cibernética, utilizando o NotebookLM.

--------------------------------------------------------------------------------
1. Contexto e Objetivos
O assunto central deste notebook é a investigação digital aplicada. Em um cenário de crescente exposição de dados e crimes cibernéticos, entender como rastrear pegadas digitais é uma habilidade crítica
. Objetivos de estudo:
Dominar o framework PIRP (Pergunta, Informação, Relação e Prova) para guiar investigações de forma autônoma;
Aprender a utilizar Google Dorks e ferramentas de OSINT para localização de pessoas e bens;
Compreender os aspectos legais e técnicos da Cadeia de Custódia e preservação de provas digitais;
Explorar o mercado de serviços, como Due Diligence empresarial e remoção de conteúdo exposto;

--------------------------------------------------------------------------------
2. Curadoria de Fontes
As fontes selecionadas equilibram a visão técnica, governamental e de mercado:
IBSEC - Blog: "10 Técnicas de Forense Digital para Investigações" (Foco em análise de memória e logs);
Bruno Fraga (YouTube/Workshop): "O Mapa da Investigação" e "80 Fontes de Dados Abertos" (Metodologia PIRP e ferramentas de OSINT);
José Milagre: "A profissão do futuro: Como ser um perito forense digital" (Carreira, legislação e perícia judicial);
Ministério da Justiça (Portal Gov.br): "POP Informática Forense" (Procedimentos operacionais padrão para exames periciais no Brasil);
EY (Ernst & Young): "10 práticas de higiene cibernética para empresas" (Gestão de risco e segurança defensiva);

--------------------------------------------------------------------------------
3. Engenharia de Prompt
Neste notebook, o raciocínio foi construído através de camadas de profundidade:

Variação 1 (Simples): "Quais as ferramentas de investigação digital?"
Resultado: A IA listou softwares, mas sem contexto estratégico.
Dificuldade: O foco em ferramentas torna o investigador dependente e "turista digital";

Variação 2 (Estratégica): "Como encontrar dados sensíveis de um cliente usando o método PIRP?"
Resposta obtida: A IA estruturou a busca começando pela Pergunta de Inteligência, passando por disciplinas como SOCMINT e IMINT, e terminando na Prova
Referência: Baseado nas aulas de Bruno Fraga sobre autonomia do investigador
Troubleshooting (Solução de problemas): Para evitar respostas genéricas sobre "investigar tudo", apliquei o framework 5W2H (O quê, Quem, Quando, Onde, Por que, Como, Quanto) nas perguntas, o que forçou a IA a entregar resultados muito mais granulares e úteis para relatórios de inteligência;

--------------------------------------------------------------------------------
4. Miniguia de Estudo
Resumos Estruturados:

Metodologia HIRP/PIRP: Toda investigação deve ter um objetivo claro (Pergunta/Hipótese). A coleta de informação é apenas o meio; o valor real está em relacionar os dados para gerar provas documentadas;

Google Hacking: O uso de operadores avançados (Dorks) como site:, filetype: e "aspas duplas" permite transformar o Google em uma ferramenta de raio-X para encontrar documentos confidenciais ou bancos de dados expostos;

Forense Corporativa: Empresas utilizam estas técnicas para Due Diligence (verificar sócios antes de investimentos) e mitigação de fraudes internas;

Glossário de Conceitos Chave
OSINT (Open Source Intelligence): Inteligência obtida através de fontes públicas e abertas;
Pivotagem: Técnica de usar um dado descoberto (como um e-mail) para expandir a investigação para outros eixos (como redes sociais ou vazamentos);
Cadeia de Custódia: Procedimentos que garantem a integridade e a história cronológica de uma evidência digital para que ela tenha validade jurídica;
Metadata (Metadados): Informações ocultas em arquivos (como data de criação e GPS de fotos) que podem revelar a origem de um documento;
SOCMINT: Inteligência focada em interações e rastros deixados em redes sociais;

Prompts Reutilizáveis para Revisão
"Atue como um analista de inteligência. Dado o identificador [INSIRA NOME/CNPJ/EMAIL], quais seriam as 5 perguntas de inteligência (5W2H) prioritárias para um dossiê de background check?"
"Explique como a Cadeia de Custódia descrita no POP do Ministério da Justiça deve ser aplicada na coleta de provas de um site que pode sair do ar a qualquer momento."
"Crie uma lista de Google Dorks específicas para buscar planilhas de gastos (XLS) vinculadas ao termo [TERMO DE BUSCA] em domínios governamentais."
