# Banco Econômico RPG — Atualizações

### Versão: `1.5.5`

# 📢 Atualização do Banco Econômico RPG

## 📋 Visão geral

A versão **1.5.5** concentra-se em correções de estabilidade, sincronização de dados e melhorias no funcionamento do sistema após a fase inicial de testes da versão 1.5.4.

Esta atualização não introduz uma nova reformulação visual. O foco é corrigir comportamentos identificados durante os testes e garantir maior consistência entre diferentes sessões e dispositivos.

## 🎨 Persistência dos temas da Loja

* Correção da persistência do tema escolhido pelo jogador.
* A preferência visual da Loja agora é vinculada à conta do jogador.
* O tema escolhido não deve mais retornar automaticamente ao tema padrão ao acessar a conta em outro navegador.
* Sincronização da preferência de tema com os dados da conta.
* O armazenamento local do navegador passa a atuar como suporte à preferência salva na conta, evitando dependência exclusiva de um único navegador ou dispositivo.

## 🔄 Sincronização entre navegadores

* Melhorias no carregamento das preferências visuais da conta.
* Correção de situações em que um navegador mantinha uma preferência diferente de outro navegador utilizando a mesma conta.
* Melhor preservação das configurações pessoais durante novos acessos.
* Ajustes no carregamento das preferências para evitar que dados antigos ou incompletos substituam configurações já existentes.

## 💰 Economia

* Correção de erro que podia impedir a abertura do painel de Economia.
* Correção de acesso inválido a informações de janelas e operações ainda não inicializadas.
* Maior proteção contra dados `null` durante o carregamento da Economia.
* Melhorias na estabilidade da abertura e renderização do painel econômico.
* Preservação das operações existentes de vilas, empresas, investimentos, fundos e ciclos econômicos.

## 🛡️ Estabilidade

* Correções pontuais identificadas durante os testes online.
* Melhor tratamento de estados que ainda não foram carregados.
* Redução de erros causados por informações temporariamente indisponíveis.
* Melhorias na inicialização de componentes que dependem de dados do Firebase.
* Manutenção das funcionalidades existentes sem alteração das regras de negócio.

## 🌐 Firebase e dados da conta

* Melhorias na persistência das preferências vinculadas ao jogador.
* Ajustes no carregamento dos dados salvos na conta.
* Melhor sincronização entre o estado local da aplicação e os dados armazenados remotamente.
* Correções para tornar as preferências do jogador mais consistentes entre diferentes sessões.

## 🧪 Continuidade dos testes

A versão `1.5.5` continua a fase de testes online do Banco Econômico RPG, agora com foco principalmente em estabilidade e consistência dos dados.

Durante os testes, pedimos que os jogadores continuem informando qualquer comportamento inesperado, especialmente:

* Tema da Loja retornando ao padrão;
* Diferenças de configuração entre navegadores;
* Problemas ao carregar a Economia;
* Erros durante operações econômicas;
* Dados que não sejam mantidos após sair e entrar novamente na conta;
* Problemas relacionados ao Firebase;
* Erros de interface ou funcionalidades que deixem de responder.

Ao identificar um problema, sempre que possível, informe o procedimento realizado e apresente uma captura de tela.

## 🤝 Contribuição da comunidade

Os testes realizados pelos jogadores continuam sendo importantes para identificar problemas que podem não aparecer durante o desenvolvimento.

Cada relato ajuda a melhorar a estabilidade e a consistência do Banco Econômico RPG antes das próximas etapas de desenvolvimento.

**Obrigado por continuar participando dos testes e contribuindo para a evolução do Banco Econômico RPG! ❤️**

---

**Banco Econômico RPG**

*Versão 1.5.5 — Correções e estabilidade*
