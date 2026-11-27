---
layout: default
title: Política de privacidade
permalink: /politica-de-privacidade/
---

# Política de privacidade

**Aplicativo:** Calebito's - Desenvolvimento Infantil  
**Responsável:** Diego Couto  
**Última atualização:** 26 de novembro de 2026 (America/Sao_Paulo)

Esta Política descreve como o aplicativo **Calebito's - Desenvolvimento Infantil** (“App”, “nós”) trata informações no dispositivo. Foi redigida em português brasileiro, com atenção a princípios da **LGPD** (Lei nº 13.709/2018) e a boas práticas alinhadas à **COPPA** (Children’s Online Privacy Protection Act) para apps infantis.

> **Resumo:** o App é **offline-first**, **sem backend próprio**, **sem anúncios** e **sem dados médicos**. Perfis, progresso e acessibilidade ficam **no aparelho**. Compras Premium, quando feitas, passam pela **Google Play** e pelo **RevenueCat**.

---

## 1. Quem somos

O App é um aplicativo Android de atividades educativas inclusivas, voltado a crianças na faixa etária indicativa de **3 a 8 anos**, com e sem deficiência, com atenção especial a dificuldades motoras. A área de configuração e assinatura é destinada a **responsáveis** (pais/cuidadores).

**Contato do responsável pelo tratamento / desenvolvedor**

- Nome: **Diego Couto**
- GitHub: [https://github.com/dccouto](https://github.com/dccouto)
- E-mail: [calebitos.app@gmail.com](mailto:calebitos.app@gmail.com)

---

## 2. Escopo e princípios

Esta Política aplica-se ao uso do App em dispositivos Android. Em especial:

| Princípio | Como o App se comporta |
|---|---|
| Minimização | Só dados necessários ao funcionamento local (perfil, progresso, acessibilidade, preferências) |
| Offline-first | Conteúdo e progresso no aparelho; sem API própria de conteúdo |
| Sem anúncios | Não há AdMob nem redes de publicidade |
| Sem dados de saúde | Não coletamos diagnóstico, laudo, CID ou dados médicos |
| Controle parental | Configurações sensíveis e “Meu Plano” ficam na área dos responsáveis |

---

## 3. Dados que o App trata **no dispositivo**

Os dados abaixo são armazenados **localmente** (SQLite/Drift e preferências do sistema no aparelho). **Não** enviamos esses dados a um servidor nosso.

### 3.1 Perfis infantis (criados pelo responsável)

- Apelido ou nome de exibição
- Avatar (identificador de imagem local)
- Faixa etária / preferências de perfil
- Datas de criação e atualização locais

### 3.2 Acessibilidade (por perfil)

- Tipo de interação (ex.: toque simples, confirmação, etapas, varredura)
- Tamanho de elementos, contraste, redução de estímulos
- Sons, animações, tempos de resposta e demais ajustes de acessibilidade

Essas configurações existem para inclusão e **não** constituem dados de saúde ou diagnóstico.

### 3.3 Progresso e uso educativo

- Atividades concluídas, tentativas, favoritos
- Histórico local de eventos de uso das atividades
- Desenhos/pinturas salvos localmente
- Conquistas desbloqueadas no aparelho

### 3.4 Preferências e cache de assinatura

- Preferências gerais do App
- Cache local do estado Premium (ex.: se o entitlement está ativo, tipo de plano, data de expiração conhecida), para funcionamento offline após uma compra

### 3.5 O que **não** coletamos

- Dados médicos, diagnósticos ou laudos
- Localização GPS
- Contatos, fotos da galeria (salvo o que o próprio App gera e guarda localmente)
- Conta de rede social da criança
- Anúncios, cookies de marketing ou “tracking” publicitário
- Backend nosso com cadastro de crianças

---

## 4. Compras, Google Play e RevenueCat

O App pode oferecer plano **Premium** (assinatura mensal e/ou compra vitalícia) processado pela **Google Play Billing**, com mediação técnica do **RevenueCat** (`purchases_flutter`).

Quando o responsável realiza ou restaura uma compra **e há conexão de rede**:

- A Google Play e o RevenueCat processam informações necessárias à compra e à validação do entitlement (por exemplo, identificadores de compra/assinatura da loja).
- O App recebe o estado da assinatura (ativo ou não) e pode guardar um **cache local** para uso offline.
- **Não** usamos o RevenueCat para anúncios nem para rastreamento publicitário.
- Cancelamento e cobrança seguem as regras da Google Play; o progresso infantil local **não** é apagado só porque a assinatura expirou.

Consulte também as políticas da Google e do RevenueCat:

- [Google Play — Privacidade](https://policies.google.com/privacy)
- [RevenueCat — Privacy](https://www.revenuecat.com/privacy)

---

## 5. Crianças, COPPA e LGPD

- O App é direcionado a crianças, mas o **responsável** configura perfis, acessibilidade e compras.
- Não solicitamos dados pessoais sensíveis da criança além do mínimo local (apelido/avatar/progresso).
- Não fazemos marketing direcionado a crianças nem exibimos anúncios.
- Não operamos um serviço online próprio de contas infantis.
- Bases legais típicas sob a LGPD, conforme o caso: **execução de contrato** / prestação do serviço solicitado no aparelho; **legítimo interesse** limitado à operação técnica da compra Premium via loja; e, quando aplicável, **consentimento** do responsável para o uso do App pela criança.

Esta Política **não** substitui aconselhamento jurídico. Em caso de dúvida regulatória, consulte um profissional habilitado.

---

## 6. Compartilhamento

Não vendemos dados. Não compartilhamos dados de perfil/progresso infantil com anunciantes.

Compartilhamento ocorre apenas:

1. **No aparelho** — os dados ficam sob controle do usuário/responsável.
2. **Google Play / RevenueCat** — apenas o necessário para processar e validar compras Premium quando o responsável usa esses recursos online.
3. **Obrigações legais** — se a lei exigir (não aplicável ao armazenamento local típico do App).

---

## 7. Retenção e exclusão

- Dados locais permanecem enquanto o App estiver instalado (ou até o responsável apagar dados/perfis no App, quando essa opção existir).
- Para remover os dados locais: desinstalar o App e/ou limpar o armazenamento do App nas configurações do Android.
- Dados de compra/assinatura podem permanecer nos sistemas da Google Play/RevenueCat conforme as políticas desses prestadores.

---

## 8. Segurança

Adotamos medidas compatíveis com um app offline-first (armazenamento local no sandbox do Android). Nenhum sistema é 100% seguro; recomendamos manter o aparelho atualizado e sob controle do responsável.

---

## 9. Transferências internacionais

O App em si não envia progresso infantil a servidores nossos. Prestadores de compra (Google, RevenueCat) podem processar dados de transação em outros países, conforme suas próprias políticas.

---

## 10. Seus direitos (LGPD)

Na medida aplicável a um app que armazena dados **localmente**, o responsável pode:

- **Acessar** e revisar os dados no próprio App (perfis, progresso, configurações)
- **Corrigir** informações editáveis de perfil e preferências
- **Eliminar** dados apagando perfis, limpando o armazenamento do App ou desinstalando
- **Contatar** o responsável (Diego Couto) pelos canais indicados nesta Política

Para exercer direitos relativos a registros de compra, use também os canais da Google Play.

---

## 11. Alterações

Podemos atualizar esta Política. A data no topo indica a versão vigente. Alterações relevantes serão refletidas neste repositório / site de documentação.

---

## 12. Contato

Dúvidas sobre privacidade:

- **Diego Couto**
- GitHub: [https://github.com/dccouto](https://github.com/dccouto)
- E-mail: [calebitos.app@gmail.com](mailto:calebitos.app@gmail.com)

Documentos relacionados: [Termos de uso](termos-de-uso.md) · [Início](index.md)
