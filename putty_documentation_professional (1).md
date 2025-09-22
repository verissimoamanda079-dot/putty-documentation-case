
# PuTTY – Conexão SSH
*2 minuto(s) de leitura*
**Documentação – PuTTY**

## Descrição
O PuTTY é um emulador de terminal gratuito e de código aberto que permite conexões remotas seguras usando o protocolo SSH (*Secure Shell*). Ele é amplamente utilizado em ambientes Windows para acessar servidores Linux e outros dispositivos de forma segura.

PuTTY foi originalmente escrito para o Microsoft Windows, mas foi portado para vários outros sistemas operacionais. Portes oficiais só estão disponíveis para algumas plataformas Unix, e em desenvolvimento para o clássico Mac OS e Mac OS X, e as versões não-oficiais foram desenvolvidas para plataformas como Symbian OS e Windows Mobile. PuTTY foi escrito e é mantido principalmente por Simon Tatham.

Com o PuTTY, os usuários podem:
- Conectar-se a servidores via SSH com autenticação segura.
- Salvar sessões para reutilização futura.
- Utilizar diferentes protocolos (SSH, Telnet, Rlogin, Raw, Serial).

Essa ferramenta garante eficiência e segurança no gerenciamento remoto de servidores.

## Funcionalidades
- **Conexão SSH segura:** permite acesso remoto a servidores com criptografia.
- **Sessões salvas:** possibilita armazenar parâmetros de conexão para reutilização.
- **Suporte a múltiplos protocolos:** SSH, Telnet, Rlogin, Raw e Serial.
- **Interface intuitiva:** facilita configuração e uso mesmo para iniciantes.

## Benefícios
- **Segurança:** conexões criptografadas e suporte a autenticação por senha ou chave SSH.
- **Produtividade:** sessões salvas economizam tempo e reduzem erros de configuração.
- **Flexibilidade:** suporta múltiplos protocolos e configurações personalizadas.

## Tutorial – Como estabelecer uma conexão SSH

**Pré-requisitos:**  
- PuTTY instalado no computador.  
- Servidor SSH acessível (IP ou hostname).  
- Credenciais de usuário válidas.  

**Passo a passo:**  
1. Abra o PuTTY.  
2. No campo *Host Name (or IP address)*, insira o endereço do servidor.  
3. Verifique se o *Port* está definido como `22`.  
4. Selecione **SSH** em *Connection type*.  
5. Clique em **Open** para iniciar a sessão.  
6. Digite seu **nome de usuário** e **senha** quando solicitado.  

**Resultado esperado:** acesso ao terminal remoto, pronto para executar comandos.

**Notas importantes:**  
- Utilize senhas fortes ou chaves SSH para maior segurança.  
- Evite usar a conta *root* diretamente; prefira usuários com permissões adequadas.  
- Salve sessões em *Saved Sessions* para facilitar reconexões futuras.
- Ao conectar pela primeira vez, o PuTTY pedirá para aceitar a chave do servidor

## Referência – Parâmetros de conexão SSH

**Requisitos do administrador/usuário:**  
- PuTTY instalado.  
- IP ou hostname do servidor.  
- Credenciais válidas.

**Caminho de acesso:**  
- Abrir PuTTY > Categoria *Session* > Configurar campos > Selecionar **SSH**.

**Campos de entrada:**

| Item                      | Tipo         | Descrição                                                   |
|----------------------------|--------------|-------------------------------------------------------------|
| Host Name (or IP address) | Campo de texto | Endereço do servidor remoto (IP ou DNS).                    |
| Port                      | Campo numérico | Porta de conexão. Padrão: `22`.                             |
| Connection type           | Botão de opção | Tipo de protocolo (SSH, Telnet, Rlogin, Raw, Serial).       |
| Saved Sessions            | Campo de texto | Armazena configurações para reutilização.                   |

**Ações disponíveis:**  
- **Open:** inicia a conexão.  
- **Save:** salva a sessão atual.  
- **Load:** carrega sessão previamente salva.  
- **Cancel:** fecha a janela de configuração.

**Informações adicionais:**  
- Por padrão, o PuTTY utiliza a porta 22 para SSH.  
- Sessões salvas podem ser reutilizadas para conexões futuras.  
- Falhas de autenticação exigem reentrada de credenciais ou encerramento da sessão.
