# 💸 App de Organização de Finanças Pessoais com Vibe Coding

## Prompt Final Gerado no Copilot

```markdown
# PRD – Aplicativo de Organização de Finanças Pessoais

## 1. Contexto
O aplicativo busca simplificar o controle financeiro pessoal por meio de interações em linguagem natural, permitindo que o usuário registre e acompanhe seus gastos sem depender de formulários complexos ou planilhas. A proposta é oferecer uma experiência conversacional, acessível e educativa.

## 2. Problema
- Usuários desistem de controlar suas finanças porque os apps atuais exigem muita entrada manual.  
- Falta de personalização e de recomendações práticas.  
- Necessidade de uma solução mais intuitiva e motivadora.

## 3. Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que desejam praticidade e simplicidade.  
- Pessoas que preferem interações naturais em vez de interfaces tradicionais.

## 4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.  
2. Classificação automática das transações (alimentação, transporte, lazer etc.).  
3. Definição e acompanhamento de metas financeiras.  
   - Cada meta deve ter um parâmetro indicando se é **mensal** (ex.: economizar R$200/mês) ou **não-mensal** (ex.: economizar R$5.000 no total).  
4. Agente Financeiro que fornece dicas de economia personalizadas.  
   - O agente deve responder apenas perguntas relacionadas a finanças pessoais.  
   - As respostas devem ser concisas, claras e sem formatações técnicas como JSON ou SQL.  
5. Relatórios simples e visuais (gráficos e resumos adaptados ao perfil do usuário).  
6. Botão de switch para alternar entre tema escuro e claro, localizado na barra superior.  

## 5. Layout Principal do Aplicativo
A tela principal será dividida horizontalmente em duas metades:  

- **Metade Esquerda:**  
  - Chat com o Agente Financeiro.  

- **Metade Direita:** Painel dinâmico que pode alternar entre três telas:  
  1. **Histórico de Transações**  
     - Botão para criar nova transação (nome, valor, categorias).  
     - Cada transação pode ser editada ou removida.  
     - Transações sem categoria informada serão categorizadas automaticamente.  
  2. **Relatório com Gráficos**  
     - Filtros por mês, tipo de transação (entrada/saída) e categoria (moradia, lazer, alimentação etc.).  
  3. **Lista de Metas**  
     - Botão para criar nova meta (nome, valor, tipo: mensal ou não-mensal).  
     - Cada meta pode ser editada ou removida.  
     - Ordem das metas pode ser alterada para organizar prioridades.  

## 6. Reatividade dos Componentes
- Qualquer alteração na base de dados (transações ou metas) deve atualizar automaticamente os componentes relevantes (chat, relatórios, listas).  
- Isso garante consistência e feedback imediato ao usuário.

## 7. Entregável da IA
- **Plano de MVP** contendo:  
  - Principais telas:  
    - Tela de chat (interação com o agente).  
    - Painel dinâmico com histórico, relatórios e metas.  
    - Barra superior com botão de switch para tema escuro/claro.  
  - Recursos necessários:  
    - Processamento de linguagem natural (NLP).  
    - Motor de categorização automática.  
    - Sistema de metas com parâmetro mensal/não-mensal.  
    - Módulo de relatórios visuais com filtros.  
    - Alternância de tema escuro/claro via botão na barra superior.  
  - Esboço de validação inicial:  
    - Testar com grupo piloto de usuários iniciantes.  
    - Avaliar engajamento (quantidade de registros via chat).  
    - Medir clareza das recomendações e relatórios.  
    - Observar preferência de uso entre tema escuro e claro.  
    - Validar se o parâmetro mensal/não-mensal nas metas é compreendido e utilizado corretamente.  
```

## Interações Adicionais no Lovable

```
Ativar o Lovable Cloud e conectar o chat ao Lovable AI para respostas inteligentes de verdade
```
```
Adicionar persistência de dados com banco de dados para que transações e metas sejam salvas entre sessões e faça com que seja possível manipular as transações e metas pelo chat e atualize os painéis após cada alteração
```


## Link do App: https://dio-lab-fin-chat.lovable.app

## Imagens do Protótipo Gerado
<img width="1212" height="889" alt="image" src="https://github.com/user-attachments/assets/34e98ce3-bf16-487b-b1d3-2a572431348c" />
<img width="1215" height="890" alt="image" src="https://github.com/user-attachments/assets/4bfdb06a-b6f5-4892-8168-3021a898473e" />
<img width="1213" height="890" alt="image" src="https://github.com/user-attachments/assets/a0ab686b-224c-4e71-bb52-937a506e2903" />

## Reflexão

### O que funcionou bem?

- O Copilot ajudou bastante na formatação do texto.
- O Lovable fez algumas melhorias no app de forma automática sem que eu precisasse especificar-las, como adicionar ícones e interações na interface (Ex: desabilitar o botão de mensagem quando o campo de texto estiver vazio).

### O que não funcionou como esperado?

- Apesar de eu ser bem explícito quanto a funcionalidade de criação de metas e transações através do chat, o Lovable não implementou isso de primeira.
- A persistência dos dados também não foi implementada na primeira versão.

### O que aprendi sobre conversar com IAs?

- Quanto mais específicas forem as instruções, maiores as chances de eu obter um resultado satisfatório.
- A IA também sabe introduzir bugs no código. 😅
