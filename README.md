# 🧠 LexIA - Integração para Obsidian

> **Potencialize sua produtividade jurídica conectando suas notas locais à Inteligência Artificial do TJMT.**

Este plugin cria uma ponte segura entre o seu cofre pessoal (Obsidian) e a plataforma **LexIA**. Com ele instalado, os agentes de IA podem consultar suas anotações para gerar contextos, resumir documentos ou rascunhar novas petições e decisões diretamente no seu computador.

---

## ✨ O que este plugin permite?

Ao conectar o Obsidian à LexIA, você habilita o assistente virtual a:

* **🔍 Ler notas específicas:** Peça para a IA analisar um resumo de processo ou jurisprudência que você salvou.
* **📝 Escrever rascunhos:** Solicite que a LexIA crie uma minuta de documento e salve diretamente em uma nova nota no seu computador.
* **🔄 Atualizar conteúdos:** Peça para a IA revisar ou complementar uma anotação existente.
* **📂 Organização:** A IA pode listar e encontrar notas para usar como base de conhecimento nas conversas.

---

## 🚀 Como Instalar

Como este é um plugin corporativo, a instalação é feita através do gerenciador **BRAT** (Beta Reviewers Auto-update Tool).

### Passo 1: Preparar o Obsidian
1.  Abra o Obsidian e vá em **Settings (Configurações)** > **Community Plugins**.
2.  Desative o "Restricted Mode" (Modo Restrito) se estiver ligado.
3.  Clique em **Browse (Navegar)** e procure por **"BRAT"**.
4.  Instale e ative o plugin **BRAT**.

### Passo 2: Adicionar o LexIA
1.  Ainda nas configurações, desça a barra lateral esquerda até encontrar o plugin **BRAT**.
2.  Clique no botão **"Add Beta plugin"**.
3.  Copie e cole o seguinte link do repositório:
    ```
    https://github.com/LexiaTJMT/lexia-obsidian-dist.git
    ```
4.  Clique em **Add Plugin**.
5.  Uma notificação confirmará a instalação. Agora, vá na lista de plugins instalados e **Ative o LexIA**.

---

## 🔗 Como Conectar

Para garantir a segurança, você precisa parear seu computador com sua conta LexIA.

1.  Acesse a **Plataforma Web LexIA** no seu navegador.
2.  Vá em **Configurações** > **Integrações**.
3.  Clique em **"Gerar Token de Acesso"** e copie o código gerado.
    * *Dica:* Se houver o botão "Conectar Automaticamente", basta clicar nele com o Obsidian aberto!
4.  No Obsidian, vá em **Settings** > **LexIA**.
5.  Cole o código no campo **"Auth Token"**.
6.  Se a conexão for bem-sucedida, você verá a mensagem: 🟢 **Conectado ao TJMT**.

---

## 🛡️ Privacidade e Segurança

Entendemos a sensibilidade dos dados jurídicos.
* **Acesso Controlado:** A LexIA **não** lê todas as suas notas. Ela acessa apenas o que você solicitar explicitamente durante uma conversa (ex: *"Leia a nota X"*).
* **Túnel Seguro:** Toda a comunicação é feita via WebSocket criptografado (WSS).
* **Dados Locais:** Seus arquivos permanecem no seu computador. O plugin apenas envia o texto necessário para o processamento da IA e recebe a resposta.

---

## ❓ Problemas Comuns

**O status está "Desconectado" 🔴**
* Verifique sua conexão com a internet.
* Certifique-se de que o token não expirou. Gere um novo na plataforma web se necessário.
* Se estiver na rede do Tribunal, verifique se não há bloqueios de firewall específicos na sua máquina.

**A IA diz que não encontrou a nota**
* Verifique se o nome do arquivo está correto. A busca é precisa, então evite abreviações não cadastradas.

---

**Desenvolvido por DPIN CJUD - TJMT**
*Dúvidas? Entre em contato com o suporte técnico.*
