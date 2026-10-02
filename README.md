# Cobertura de Garagens — Condomínio Palmeira Azul

*Read this in other languages: [English](README-en.md)*

---

Página web estática e interativa destinada à apresentação de um estudo conceitual de cobertura contínua para as vagas de garagem do Condomínio Palmeira Azul, em Palmas (TO). O projeto utiliza um modelo tridimensional em formato GLB para permitir a inspeção visual da proposta por diferentes ângulos.

## Funcionalidades

- visualização interativa do modelo 3D publicado em `modelo.glb`;
- controles para vista inicial, frontal e superior;
- rotação automática opcional do modelo;
- zoom e navegação por mouse ou gestos de toque;
- abertura local de outro arquivo `.glb`, sem substituir o modelo publicado;
- mensagens de carregamento e tratamento de erros no visualizador;
- apresentação explícita do caráter conceitual do estudo e da necessidade de conferência técnica antes de uma eventual execução;
- arquivos CSV e XLSX com empresas e fornecedores levantados para consulta de orçamento.

## Tecnologias e arquivos principais

- **HTML5, CSS e JavaScript** em um único arquivo principal, `index.html`;
- **`<model-viewer>` 4.0.0**, carregado via CDN, para renderização e interação com modelos 3D;
- **GLB** para o modelo tridimensional da proposta;
- **CSV/XLSX** para o levantamento de empresas e fornecedores.

### Estrutura do repositório

- `index.html` — página principal e lógica do visualizador;
- `modelo.glb` — modelo tridimensional carregado por padrão;
- `Empresas_para_Orcamento_Cobertura_Garagens.csv` — levantamento de empresas em formato CSV;
- `Empresas_para_Orcamento_Cobertura_Garagens.xlsx` — versão em planilha do mesmo levantamento.

## Uso

Abra `index.html` em um navegador com acesso à internet para que a biblioteca `model-viewer` possa ser carregada pelo CDN. O modelo `modelo.glb` deve permanecer no mesmo diretório da página para ser carregado automaticamente.

Após o carregamento, é possível arrastar o modelo para girá-lo, usar a roda do mouse ou gestos de toque para aproximar e afastar e selecionar vistas predefinidas. O botão **Abrir outro modelo** permite visualizar temporariamente um arquivo GLB do dispositivo do usuário. Esse arquivo permanece apenas no navegador e não modifica o conteúdo publicado no repositório.

## Limitações e caráter do estudo

O conteúdo apresentado é um **estudo conceitual**. As dimensões indicadas pelo modelo são provisórias, e a solução final depende da conferência das plantas, da elaboração de projeto técnico, da avaliação de custos e das aprovações aplicáveis. O repositório não documenta validação estrutural, dimensionamento executivo ou aprovação técnica da solução.

## 👤 Autoria e desenvolvimento

Página web interativa de visualização 3D desenvolvida de forma independente por **Pablo Phillipe Cândido dos Santos**, destinada a apoiar a apresentação e a discussão de uma proposta conceitual de cobertura para as garagens do Condomínio Palmeira Azul, com navegação por diferentes vistas do modelo e consulta complementar a um levantamento de possíveis fornecedores.

O desenvolvimento contou com a utilização de ferramentas de inteligência artificial generativa como recurso auxiliar no processo de desenvolvimento, mantendo-se sob responsabilidade do autor a concepção, implementação, integração e verificação do projeto.

Currículo Lattes: [http://lattes.cnpq.br/9500873674712528](http://lattes.cnpq.br/9500873674712528)
