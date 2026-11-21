O **Stitch** (ferramenta de design de interfaces com IA do Google, acessível em `stitch.withgoogle.com` ou via o domínio indicado pelo seu professor) permite gerar protótipos visuais de alta fidelidade e código frontend (HTML/CSS/React) diretamente a partir de descrições em texto (prompts).

Para o seu ensaio de pré-projeto da **Proposta 4 (Banco Comunitário de Micro-Serviços)**, o objetivo no Stitch é gerar as **4 telas principais do MVP** com consistência visual, acessibilidade (botões grandes, alto contraste) e foco em dispositivos móveis (*Mobile-First*).

---

### Passo a Passo para Criar o Protótipo no Stitch

#### Passo 1: Configuração Inicial do Projeto

1. Acesse a plataforma indicada pelo professor e faça login com sua conta Google.
2. Crie um novo projeto e dê o nome do seu aplicativo (ex: **VizinhoForte** ou **TrampoLocal**).
3. Na configuração de viewport/dispositivo, selecione **Mobile (390x844)** — já que 90% do público-alvo (moradores e trabalhadores informais) acessará via smartphone.
4. Defina a paleta de cores base no prompt inicial: **Verde Esmeralda (`#10B981`)** para ações principais e botão do WhatsApp, **Azul Escuro (`#0F172A`)** para textos e confiança, e fundo claro (`#F8FAFC`) para leitura fácil sob a luz do sol.

---

#### Passo 2: Gerando as 4 Telas do MVP (Prompts Prontos)

No Stitch, você constrói a interface por etapas, refinando cada tela. Copie e cole os prompts abaixo (em inglês ou português, o Stitch entende ambos, mas em português já gera os textos reais da interface):

##### Tela 1: Vitrine Hiperlocal (Home do Morador — Sem Login)

> *"Crie uma tela inicial mobile-first para um aplicativo comunitário brasileiro de micro-serviços de bairro. No topo, uma barra simples mostrando a localização atual ('Bairro Benfica • Raio de 2 km') com botão para alterar, e um campo de busca grande ('Qual serviço você precisa hoje?'). Logo abaixo, ícones grandes de categorias horizontais: Eletricista, Diarista, Pedreiro, Costura, Frete. Na área principal, uma lista de cards de trabalhadores locais. Cada card deve conter: foto de perfil, nome, profissão, uma tag verde 'Livre Hoje', distância ('a 450m de você'), selos de confiança da vizinhança ('Pontual', 'Preço Justo') e um botão verde largo no rodapé do card escrito 'Chamar no WhatsApp'. Design limpo, fontes grandes, alto contraste e acessível."*

##### Tela 2: Perfil do Trabalhador e Avaliações da Vizinhança

> *"Crie a tela de detalhes do perfil de um trabalhador autônomo neste mesmo aplicativo. No topo, foto, nome completo ('Carlos Silva — Eletricista Residencial'), tempo no bairro ('Mora no bairro há 8 anos') e selo 'Livre Hoje'. Abaixo, uma seção com descrição curta dos serviços realizados e faixa de preço ('A partir de R$ 60,00'). Em seguida, um bloco de 'Confiança da Vizinhança' mostrando contadores de selos: '18x Pontual', '14x Preço Justo', '11x Caprichoso', seguido por 2 comentários curtos de moradores. No rodapé fixo da tela, um botão verde de destaque com ícone do WhatsApp: 'Pedir Orçamento no WhatsApp'."*

##### Tela 3: Painel do Trabalhador ("Modo Prestador")

> *"Crie a tela de painel de controle (dashboard) do trabalhador autônomo. No topo, um cartão de destaque com um interruptor (toggle switch) grande ativado em verde: 'Estou Livre Hoje (Visível no topo das buscas)'. Logo abaixo, um resumo financeiro simples do mês: 'Ganhos registrados em Novembro: R$ 2.450,00' com uma barra de progresso discreta e o texto '14 serviços concluídos'. No centro, dois botões grandes de ação rápida: 'Emitir Recibo Digital (PDF)' e 'Editar Meus Serviços'. Na parte inferior, uma lista dos últimos recibos emitidos com nome do cliente, data e valor."*

##### Tela 4: Gerador de Recibo Comunitário (Comprovante de Renda)

> *"Crie uma tela de formulário simples e uma pré-visualização de recibo digital para trabalhador autônomo. Na parte superior, 3 campos grandes: 'Nome do Cliente', 'Serviço Realizado' e 'Valor Recebido (R$)'. Na metade inferior da tela, mostre o cartão visual do recibo gerado, com aparência de documento oficial limpo, contendo: título 'COMPROVANTE DE PRESTAÇÃO DE SERVIÇO', dados do prestador, valor, data, código de validação único ('#VIZ-8492') e um botão azul para 'Baixar PDF' e outro botão verde para 'Enviar Recibo no WhatsApp'."*

---

#### Passo 3: Refinamento e Consistência Visual

Após gerar cada tela, use o painel de edição do Stitch para ajustar detalhes importantes antes de exportar:

* **Tamanho de toque:** Verifique se os botões têm altura suficiente para dedos (mínimo de `44px` a `48px`), facilitando o uso por trabalhadores manuais e idosos.
* **Remoção de ruído:** Peça ao Stitch para remover menus hambúrguer complexos ou gráficos financeiros avançados; mantenha no máximo **3 itens na barra de navegação inferior**: `Buscar`, `Meus Recibos` e `Meu Perfil`.

**Autor:João Silvano**Disciplina:Fullstack**Professor Robson**Prototipo interativo (Stich)**
