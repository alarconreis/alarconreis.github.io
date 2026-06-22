# Política de Privacidade — TricoHub

**Última atualização:** junho de 2026

---

## 1. Sobre o TricoHub

O TricoHub é um aplicativo de diário capilar que ajuda você a registrar e acompanhar sua rotina de cuidados com o cabelo, incluindo o registro da queda capilar, produtos utilizados, anotações e fotos de evolução. O aplicativo também permite que você, de forma opcional e mediante consentimento, conecte-se a um profissional de saúde (tricologista) para que ele acompanhe sua evolução.

Este documento descreve como o TricoHub coleta, utiliza, armazena, compartilha e protege suas informações pessoais, em conformidade com a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018).

---

## 2. Controlador dos Dados

O responsável pelo tratamento dos dados pessoais coletados pelo TricoHub é:

**TricoHub**
Contato: contato@tricohub.com.br
Encarregado de dados (DPO) / privacidade: contato@tricohub.com.br

---

## 3. Quais dados coletamos

### 3.1 Dados de identificação e conta

- **Nome e e-mail:** utilizados para criar e identificar sua conta e personalizar a experiência.

### 3.2 Dados de saúde (dados pessoais sensíveis)

Os dados abaixo, por se referirem à sua saúde capilar, são tratados como **dados pessoais sensíveis** nos termos do Art. 11 da LGPD e recebem proteção reforçada:

- **Objetivo de cuidado capilar:** definido por você na configuração inicial.
- **Rotina capilar:** produtos e itens de cuidado cadastrados por você.
- **Contagem de queda diária:** número de fios registrados por dia.
- **Anotações diárias:** observações pessoais livres.
- **Fotos de evolução capilar:** imagens que você opta por registrar e enviar para acompanhamento.

### 3.3 Dados técnicos

- **Token de notificação (push):** identificador técnico do dispositivo, usado exclusivamente para enviar os lembretes e notificações que você configurar. Registramos o token e a plataforma (iOS ou Android).

### 3.4 Dados que NÃO coletamos

O TricoHub **não coleta**:

- Dados de localização (GPS).
- Dados financeiros ou de pagamento (o aplicativo é gratuito).
- Dados de publicidade ou rastreamento para fins de marketing.
- Dados de terceiros sem o seu conhecimento.

---

## 4. Como e onde armazenamos seus dados

Seus dados são armazenados em duas camadas:

- **No seu dispositivo:** em banco de dados local criptografado (SQLCipher), protegido pelo sandbox do sistema operacional (iOS / Android).
- **Em servidor seguro (nuvem):** para permitir o backup, a sincronização entre dispositivos e o acompanhamento pelo profissional que você autorizar, seus dados são sincronizados e armazenados de forma segura na infraestrutura do **Supabase** (provedor de banco de dados e armazenamento que atua como operador dos dados, sob nossas instruções).

A transmissão entre o aplicativo e o servidor é protegida por criptografia em trânsito (HTTPS/TLS).

---

## 5. Como protegemos seus dados

O TricoHub adota as seguintes medidas de segurança:

- **Criptografia em repouso:** o banco de dados local utiliza SQLCipher; os dados no servidor são protegidos pelos controles de segurança do provedor.
- **Criptografia em trânsito:** toda a comunicação com o servidor usa HTTPS/TLS.
- **PIN de 4 dígitos:** proteção de acesso opcional configurada por você.
- **Biometria:** suporte a Face ID (iOS) e impressão digital (Android e iOS).
- **Timeout automático:** o aplicativo solicita autenticação após período de inatividade.
- **Controle de acesso:** o acesso aos seus dados pelo profissional só ocorre após vínculo e consentimento explícito seu (ver seção 6).
- **Registro de auditoria:** acessos e ações sobre os dados são registrados para fins de segurança e conformidade.

---

## 6. Compartilhamento de dados com profissional de saúde

O TricoHub permite que você se conecte a um profissional de saúde (tricologista) para acompanhamento. Este compartilhamento:

- É **opcional** e ocorre **somente por sua iniciativa**, ao vincular-se a um profissional.
- Exige o seu **consentimento explícito e específico**, registrado no aplicativo.
- Pode ser **revogado a qualquer momento** por você, encerrando o acesso do profissional aos seus dados.

Quando você autoriza o vínculo, o profissional vinculado pode acessar os dados capilares necessários ao acompanhamento (registros de queda, rotina, anotações e fotos de evolução). O TricoHub **não compartilha, vende ou transfere** seus dados a terceiros para qualquer outra finalidade, e **não os utiliza para publicidade**.

---

## 7. Serviços de terceiros (operadores)

O TricoHub utiliza os seguintes serviços, que atuam como operadores e estão sujeitos às suas próprias políticas de segurança e privacidade:

- **Supabase:** infraestrutura de banco de dados, autenticação e armazenamento de arquivos.
- **Expo:** plataforma de desenvolvimento e serviço de envio de notificações push.

Esses operadores tratam os dados sob nossas instruções e exclusivamente para viabilizar o funcionamento do aplicativo.

---

## 8. Autenticação

O acesso à sua conta é feito por e-mail, com verificação por código de uso único (OTP) enviado ao seu e-mail. Não utilizamos login por redes sociais.

---

## 9. Por quanto tempo mantemos seus dados

Mantemos seus dados enquanto sua conta estiver ativa e pelo tempo necessário para as finalidades descritas nesta política. Ao solicitar a exclusão, seus dados são removidos, ressalvadas as informações que precisem ser retidas por obrigação legal.

---

## 10. Seus direitos (LGPD)

De acordo com a LGPD, você tem os seguintes direitos sobre seus dados pessoais:

- **Acesso:** consultar seus dados a qualquer momento no aplicativo.
- **Correção:** editar seu nome e e-mail em Configurações → Perfil.
- **Exclusão:** apagar seus dados em Configurações (e solicitar a exclusão dos dados no servidor pelo e-mail de privacidade).
- **Portabilidade:** exportar seus dados por meio do relatório em PDF.
- **Revogação do consentimento:** desativar funcionalidades ou encerrar o vínculo com um profissional a qualquer momento.
- **Informação sobre compartilhamento:** saber com quem seus dados são compartilhados.

Para exercer direitos que não possam ser realizados diretamente no aplicativo, entre em contato pelo e-mail privacidade@tricohub.com.br.

---

## 11. Base legal (LGPD)

O tratamento dos dados pessoais pelo TricoHub baseia-se nas seguintes hipóteses legais:

- **Consentimento (Art. 7º, I e Art. 11, I):** para o tratamento de dados pessoais e, em especial, dos dados de saúde (dados sensíveis), incluindo o compartilhamento com o profissional que você autorizar.
- **Execução de contrato (Art. 7º, V):** para a prestação do serviço de diário capilar.
- **Tutela da saúde (Art. 11, II, "f"):** quando aplicável, para procedimento realizado por profissional de saúde a quem você se vinculou.

---

## 12. Dados de crianças e adolescentes

O TricoHub é destinado a maiores de 18 anos e não é direcionado a menores. Não coletamos intencionalmente dados de menores. Se você acredita que um menor forneceu dados ao aplicativo, entre em contato pelo e-mail contato@tricohub.com.br para que possamos removê-los.

---

## 13. Alterações nesta política

Esta política pode ser atualizada periodicamente. Quando houver alterações relevantes, você será avisado por meio de aviso no aplicativo. A data da última atualização está sempre indicada no início deste documento.

---

## 14. Contato

Dúvidas sobre esta Política de Privacidade ou sobre o tratamento dos seus dados:

**E-mail:** contato@tricohub.com.br
**Privacidade / DPO:** contato@tricohub.com.br

---

*Este documento foi elaborado em conformidade com a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018) e com as diretrizes das lojas de aplicativos (Apple App Store e Google Play Store).*
