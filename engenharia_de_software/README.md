# Atividades da disciplina 

### Atividade 1
##### Software é intangível
<br>

**>Comentar com suas palavras o trecho do livro 'Software Engineering at Google' (Slide 4):**
<br>

**Comentário**

Engenharia de software vai além da programação, pois envolve aplicar conhecimento teórico para construir sistemas reais, mesmo que intangíveis. Diferente de outras engenharias, ainda não possui práticas tão rigorosas, mas isso precisa mudar, já que falhas em software têm impactos cada vez mais significativos na sociedade. Portanto, é necessário adotar métodos mais estruturados e confiáveis no desenvolvimento de software.

---

### Atividade 2
##### Engenharia de Software = Programação + tempo, escalabilidade e trade-offs
<br>

**>Comentar com suas palavras o trecho do livro 'Software Engineering at Google' (Slide 4):**
<br>

**Comentário**

Engenharia de software envolve não apenas programar, mas manter o código útil ao longo do tempo. Isso exige práticas que garantam sua adaptação a mudanças, crescimento e evolução do sistema. O conceito de “programação ao longo do tempo” destaca que o software deve ser sustentável durante todo seu ciclo de vida. Para isso, é fundamental considerar três aspectos: adaptação a mudanças, crescimento em escala e tomada de decisões baseada em custos e trade-offs.

---

### Atividade 3
##### Requisitos não funcionais
<br>

**>Listar 5 requisitos não funcionais e descrevê-los com suas palavras (Slides 8, 9 e 10):**
<br>

**Robutness (Robustez):**

Robustez é a capacidade de um sistema continuar funcionando mesmo diante de erros, entradas inválidas ou situações inesperadas. Um sistema ‘robusto’ lida bem com falas sem comprometer completamente sua operação.
Exemplo: Um sistema de login que, ao receber uma senha incorreta ou dados inválidos, não trava nem apresenta erro crítico, apenas informa ao usuário que os dados estão incorretos.

**Scalability (Escalabilidade):**

Escalabilidade de um sistema é a capacidade dele suportar o aumento de carga, seja de usuários, dados ou requisições, sem perda significativa de desempenho, podendo crescer de forma eficiente conforme a demanda.
Exemplo: Uma loja online que consegue atender tanto 10 quanto 10.000 usuários simultâneos sem ficar lenta ou sair do ar.

**Recoverability (Recuperabilidade):**

Um sistema com recuperabilidade tema a capacidade de se recuperar rapidamente após falas, restaurando seu funcionamento normal e minimizando perda de dados ou impacto para o usuário.
Exemplo: Um sistema que salva automaticamente os dados e, após uma queda de energia, permite recuperar as informações sem perda significativa.

**Extensibility (Extensibilidade):**

Um programa que consegue ser expandido com novas funcionalidade sem exigir grandes modificações na estrutura existente, possui extensibilidade.
Exemplo: Um aplicativo que permite adicionar um novo método de pagamento sem precisar reescrever todo o sistema de compras.

**Modularity (Modularidade):**

É a capacidade de um sistema de ser dividido em partes independentes, chamadas módulos. Isso facilita a manutenção, reutilização de código e o seu desenvolvimento.
Exemplo: Um sistema em que o módulo de cadastro de usuários funciona separado do módulo de pagamentos, permitindo alterar um sem afetar o outro.

---

### Atividade 4
##### Trade-offs = negociação entre requisitos não funcionais
<br>

**>Citar e descrever 3 cenários de trade-offs (Slide 12, usar outros exemplos)**
<br>

**1. Python vs C++**

Trade-off: Produtividade vs Performance

Python é mais simples e rápido de desenvolver, com sintaxe mais limpa e menos código. Em compensação, tem menor desempenho.
 C++ oferece alta performance e controle de memória, sendo ideal para sistemas críticos, mas é mais complexo e demanda mais tempo de desenvolvimento.

**2. Apple vs Google**

Trade-off: Ecossistema fechado vs aberto

A Apple prioriza controle e integração entre dispositivos, oferecendo experiência mais consistente.
O Google adota abordagem mais aberta, com maior flexibilidade, mas menos padronização.

**3. Notion vs Obsidian**

Trade-off: Praticidade e integração vs Controle e personalização

O Notion oferece uma plataforma completa, com diversas funcionalidades integradas, sendo mais prático para organizar informações em um único lugar. No entanto, depende da internet e possui menos flexibilidade de personalização profunda.
O Obsidian funciona localmente, oferecendo maior controle sobre os dados e alta personalização por meio de plugins e configurações. Em contrapartida, exige mais configuração inicial e não possui tantas funcionalidades integradas prontas como o Notion.
