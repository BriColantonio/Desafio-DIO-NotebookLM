# 🔐 Segurança de Computadores – Guia Básico

Este repositório reúne anotações que fiz utilizando o **NotebookLM** para estudar **boas práticas de segurança em computadores**.  

O objetivo é organizar informações importantes sobre:
- Como manter um computador seguro
- Como identificar possíveis infecções por vírus
- Como analisar programas suspeitos
- Boas práticas de backup e proteção de dados

---

# 🛡️ Como manter seu computador seguro

Manter um computador seguro exige **ferramentas de proteção e hábitos de navegação responsáveis**. Abaixo estão algumas das práticas mais importantes.

## 1️⃣ Proteção de Software e Sistema

### Atualizações do sistema
Manter o sistema operacional e os programas atualizados é essencial, pois atualizações corrigem **falhas de segurança exploradas por invasores**.

No Windows, é recomendado:
- Ativar **Windows Update automático**
- Atualizar programas como **Microsoft Office e navegadores**

### Uso de antivírus
Um antivírus ajuda a **detectar e remover malware em tempo real**.

No Windows já existe uma solução integrada:

**Microsoft Defender (Segurança do Windows)**

Boas práticas:
- Utilizar apenas **um antivírus ativo**
- Evitar instalar antivírus de empresas diferentes ao mesmo tempo

### Firewall
O **Firewall do Windows** deve permanecer ativado para bloquear conexões não autorizadas.

### Controle de Conta de Usuário (UAC)
O **UAC** impede que programas façam alterações críticas no sistema sem autorização do usuário.

Também é recomendado manter ativada a:

**Proteção contra Adulteração (Tamper Protection)**.

---

# 👤 Gestão de Identidade e Acesso

## Senhas fortes
Uma senha segura deve conter:

- Letras maiúsculas
- Letras minúsculas
- Números
- Símbolos

Além disso:

- Nunca reutilizar a mesma senha em vários serviços.

## Autenticação de Dois Fatores (2FA)

O **2FA** adiciona uma camada extra de segurança.

Mesmo que alguém descubra sua senha, ainda será necessário um segundo fator de autenticação, como:

- Código por SMS
- Aplicativo autenticador
- E-mail de confirmação

## Gerenciadores de senha

Evite salvar senhas em computadores públicos.

Use gerenciadores de senha integrados aos navegadores modernos ou aplicativos especializados.

---

# 🌐 Hábitos seguros na internet

## Cuidado com e-mails suspeitos (Phishing)

Ataques de phishing geralmente utilizam:

- Links maliciosos
- Anexos infectados
- Mensagens que parecem vir de empresas confiáveis

Sempre verifique:
- remetente
- domínio do link
- conteúdo da mensagem

## Downloads seguros

Baixe softwares **somente de sites oficiais**.

Evite:

- programas piratas
- softwares crackeados
- downloads de sites não confiáveis

Esses arquivos frequentemente contêm **malware escondido**.

## Navegadores seguros

Utilizar navegadores modernos ajuda na proteção contra sites maliciosos.

Exemplo:

- Microsoft Edge
- Google Chrome

Eles possuem recursos como:

- bloqueio de pop-ups
- filtros de segurança (SmartScreen)

---

# 💾 Backup e proteção de dados

## Backups regulares

Backups são fundamentais para proteger dados contra:

- falhas de hardware
- vírus
- ransomware
- exclusões acidentais

Uma das melhores práticas é utilizar:

**Backup em nuvem (Cloud Backup)**

Vantagens:

- armazenamento externo
- proteção contra danos físicos
- recuperação rápida de arquivos

---

# 🔌 Cuidado com dispositivos externos

Evite conectar ao computador:

- pendrives desconhecidos
- HDs externos de procedência duvidosa

Dispositivos USB podem conter **malware que executa automaticamente no sistema**.

---

# 🦠 Como saber se o computador está infectado

Alguns sinais comuns de infecção incluem:

### Lentidão excessiva
O computador fica muito mais lento do que o normal.

### Travamentos frequentes
O sistema trava ou reinicia inesperadamente.

### Pop-ups e anúncios
Janelas e propagandas aparecem mesmo sem abrir o navegador.

### Programas desconhecidos
Softwares aparecem instalados sem que você tenha feito a instalação.

### Alterações nas configurações de segurança
Alguns vírus tentam desativar o antivírus ou alterar configurações do sistema.

---

# 🔍 Como verificar se existe malware

## 1. Fazer uma varredura completa

Execute uma análise completa com o antivírus.

No Windows:

**Segurança do Windows → Verificação completa**

## 2. Microsoft Defender Offline

Alguns malwares conseguem se esconder dentro do sistema.

O **Microsoft Defender Offline** reinicia o computador e executa uma verificação antes do Windows iniciar, aumentando a chance de detectar ameaças ocultas.

## 3. Verificar aplicativos instalados

Caminho no Windows:
Iniciar → Configurações → Aplicativos


Procure por:

- programas desconhecidos
- softwares instalados recentemente
- aplicativos de origem duvidosa

Se encontrar algo suspeito, desinstale.

---

# ⚠️ Como identificar programas suspeitos

Alguns sinais de alerta:

- Programas que você **não lembra de ter instalado**
- Softwares instalados junto com outros programas (**bundled software**)
- Aplicativos de **fontes não oficiais**
- Programas instalados na mesma data em que o computador começou a apresentar problemas

Após remover programas suspeitos:

1. Execute uma nova varredura antivírus
2. Reinicie o computador
3. Verifique se o problema foi resolvido

---

# 📚 Objetivo deste repositório

Este material foi organizado como parte dos meus estudos sobre:

- Segurança da Informação
- Boas práticas de uso de computadores
- Diagnóstico básico de malware

Todas as informações foram analisadas e resumidas a partir de pesquisas feitas no **NotebookLM**.

Links das fontes:
https://support.microsoft.com/pt-br/windows/proteger-meu-computador-contra-v%C3%ADrus-b2025ed1-02d5-1e87-ba5f-71999008e026
https://brasilcloud.com.br/10-maneiras-de-proteger-seu-computador/
https://support.microsoft.com/pt-br/topic/manter-o-computador-seguro-na-resid%C3%AAncia-c348f24f-a4f0-de5d-9e4a-e0fc156ab221
https://www.youtube.com/watch?v=nphKpNFHQd8
https://www.youtube.com/watch?v=zQK_ZChXI5I

---
