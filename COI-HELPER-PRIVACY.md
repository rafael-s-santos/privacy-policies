# Política de Privacidade da Extensão "COI Helper"

**Última atualização: 25 de outubro de 2025**

Esta política de privacidade rege o uso da extensão "COI Helper" ("a Extensão") para o Google Chrome, criada por Rafael Silva dos Santos.

## 1. Coleta e Uso de Informações

A Extensão "COI Helper" **NÃO** coleta, armazena, vende ou transmite quaisquer dados pessoais identificáveis ou de navegação do desenvolvedor ou para serviços de terceiros.

Toda a funcionalidade da extensão é processada localmente no navegador do usuário.

## 2. Dados Manipulados pela Extensão

Para executar suas funções, a Extensão manipula dois tipos de dados:

### a) Configuração da Console (Armazenamento Local)

A Extensão permite que o usuário salve sua preferência de console (ex: "PC01" a "PC59"). 
* **Onde é salvo:** Esta preferência é salva usando a API `chrome.storage.sync`.
* **Quem tem acesso:** A informação é armazenada localmente no seu navegador e sincronizada *apenas* com a sua própria conta Google. O desenvolvedor **não tem acesso** a esta informação.

### b) Texto Selecionado (Menu de Contexto)

Quando o usuário clica com o botão direito em um texto selecionado e usa a função "SEGUIR PARA... (Byne ou WPA)", a Extensão lê esse texto.
* **Como é usado:** O texto selecionado (um número de telefone ou número de nota) é tratado e usado para preencher os campos em **sistemas web internos da empresa (o sistema "Byne" e o portal "WPA")**.
* **Quem tem acesso:** Esta informação é enviada *exclusivamente* para os servidores internos da empresa do usuário, conforme solicitado pela ação do próprio usuário. O desenvolvedor **não tem acesso**, não armazena e não transmite este dado para nenhum outro local.

## 3. Permissões Solicitadas

* **contextMenus:** Para criar o menu "SEGUIR PARA..." no clique com o botão direito.
* **storage:** Para salvar a preferência de console do usuário localmente.
* **scripting / host_permissions:** Para poder preencher os campos e clicar no botão na **página interna do sistema "Byne"**.
* **tabs:** Para abrir as novas abas do Byne e WPA, e fechar a aba do Byne após a conclusão.

## 4. Contato

Se você tiver alguma dúvida ou preocupação sobre esta Política de Privacidade, sinta-se à vontade para [abrir uma "issue" no repositório de políticas](https://github.com/rafael-s-santos/privacy-policies/issues).
