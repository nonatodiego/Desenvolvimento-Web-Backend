# Arquitetura de Software

<aside>
💡 Na arquitetura de software, o conceito de "grande bola de lama" refere-se a um sistema que é mal projetado e complexo. Essa expressão é usada para descrever um sistema no qual a estrutura é confusa e as funcionalidades são adicionadas de forma desorganizada. Isso resulta em dependências confusas entre os componentes e dificuldades na manutenção, testes e modificações. Uma grande bola de lama na arquitetura de software pode causar problemas de qualidade e desempenho. Portanto, é essencial evitar o desenvolvimento de sistemas desse tipo, priorizando uma arquitetura bem projetada, modular e de fácil compreensão.

</aside>

![bola-de-lama](https://miro.medium.com/v2/resize:fit:600/0*EWjybLwJbxllHPFo)

`Ex: Grande bola de lama`

De acordo com a ISO/IEC/IEEE 42010, arquitetura de software pode ser definida como:

> *Conceitos ou propriedades fundamentais de um sistema em seu ambiente incorporados em seus elementos, relacionamentos e nos princípios de seu design e evolução.*
> 

---

## Padrão apresenta os seguintes pontos principais

- Uma arquitetura de software é uma parte fundamental de um sistema de software;
- Um sistema de software está situado em um ambiente, e sua arquitetura de software leva em consideração o ambiente no qual deve operar;
- Uma descrição da arquitetura documenta a arquitetura e comunica às partes interessadas como a arquitetura atende às necessidades do sistema;
- As visualizações de arquitetura são criadas a partir da descrição da arquitetura, e cada visualização cobre uma ou mais questões de arquitetura das partes interessadas.

---

## Arquitetura de Software - **`Aula`**

- Conceito de **`“Grande bola de Lama”`**

### Arquitetura

- A arquitetura de um software representa a estrutura de um sistema, compreendida por:
    - `Componentes` ou blocos de construção
    - `Propriedades` visíveis externamente `desses componentes`
    - `Relacionamento entre entre`
    
    ### Arquitetura de um site dinâmico
    
    [arquitetura-site-dinamico](https://raw.githubusercontent.com/nonatodiego/Desenvolvimento-Web-Backend/main/images/arquitetura-site-dinamico.png)
    

## Estilos de Arquitetura

- Uma arquitetura de software pode ser classificada segundo `estilos de arquitetura`, que são formas de organizar o sistema, conferindo assim determinado grau de uniformidade a ela
- Um estilo é baseado em um `conjunto de padrões`, `modelos` e `recursos` que funcionam como elementos básicos para a construção do produto
- A `arquitetura` de um sistema `pode aderir a um ou mais estilos arquiteturais`
- Esses estilos podem `simplificar o problema` de definição da arquitetura do sistema
- Cada estilo de arquitetura lida com `diferentes atributos de qualidade`

## Características Arquiteturais - **`Aula`**
- Uma solução de software consiste em `requisitos de domínio` e `características arquitetônicas`
- Não existe um padrão universal para descrever as características de uma arquitetura
    - Evolução rápida do ecossistema de software
    - Novos conceitos, medidas…

---

### Operacional

- Desempenho
- Escalabilidade
- Elasticidade
- Disponibilidade
- Confiabilidade
- Etc..

### Estrutural

- Modularidade
- Acoplamento
- Legibilidade
- Configurabilidade
- Portabilidade
- Etc..

### Transversal

- Segurança
- Acessibilidade
- Autenticação
- Autorização
- Etc..

---

## Características Operacionais

- `Disponibilidade`
    - Por quanto tempo o sistema precisará estar disponível
- `Continuidade`
    - Capacidade de recuperação de desastres
- `Desempenho`
    - Desempenho do sistema é utilizado para se referir ao tempo de resposta em um sistema não carregado
- `Recuperabilidade`
    - Requisitos de continuidade de negócios. Por exemplo, em caso de desastre, com que rapidez o sistema deve estar on-line novamente?

- `Confiabilidade`
    - Avalie se o sistema precisa ser à prova de falhas ou se é de missão crítica de uma forma que afeta vidas
- `Robustez`
    - Capacidade de lidar com erros e condições de limite durante a execução
- `Escalabilidade`
    - Capacidade do sistema de funcionar e operar conforme o número de usuários ou solicitações aumenta

## Características Estruturais

- `Configurabilidade`
    - Capacidade para os usuários finais alterarem facilmente aspectos da configuração do software
- `Extensibilidade`
    - Capacidade de conectar novas funcionalidades
- `Instabilidade`
    - Facilidade de instalação do sistema em todas as plataformas necessárias
- `Localização`
    - Suporte para vários idiomas, caracteres, unidades de medida, moeda, etc…

- `Manutenção`
    - É fácil aplicar mudanças e aprimorar o sistema?
- `Portabilidade`
    - Capacidade de ser compilado ou executado em diferentes ambientes
- `Suportabilidade`
    - Qual nível de suporte técnico é necessário?
- `Atualização`
    - Capacidade de atualizar com facilidade

## Características Transversais

- `Acessibilidade`
    - Acesso a todos os seus usuários, incluindo aqueles com deficiências como daltonismo ou perda auditiva
- `Arquivabilidade`
    - Os dados precisarão ser arquivados ou excluídos após um período de tempo?
- `Autenticação`
    - Requisitos de segurança para garantir que os usuários sejam quem dizem ser
- `Autorização`
    - Requisitos de segurança para garantir que os usuários possam acessar apenas certas funções dentro do sistema

## Trade-Offs

- `Privacidade`
    - Capacidade de ocultar transações de funcionários internos da empresa
- `Segurança`
    - Os dados precisam ser criptografados no banco de dados?
- `Legal`
    - Em quais restrições legislativas o sistema opera
- `Usabilidade`
    - Nível de treinamento necessário para que os usuários atinjam seus objetivos com o sistema
- Os sistemas podem suportar apenas algumas das características, pois cada característica da arquitetura frequentemente causa impacto nas outras
    - `Segurança` x `Desempenho`

## Dica

<aside>
💡 Nunca almeje a melhor arquitetura, mas sim a menos pior

</aside>