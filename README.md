# 💜 LeafCore
* Versões testadas: **1.7, 1.8**.

## Compatibilidade
Este plugin também é responsável pelas compatibilidades de outros plugins Leaf. Permitindo que funcione em diferentes versões de Spigot. 

## Replaces 
Estes são os replaces padrões, que você poderá utilizar em qualquer configuração de texto de outros plugins Leaf.

```
%leaf_nome% - Nome do servidor.
%leaf_prefix% - Prefixo do servidor.
%leaf_site% - Site do servidor.
%leaf_discord% - Discord do servidor.
%leaf_forum% - Forum do servidor.
%leaf_loja% - Loja do servidor.
```

Estas informações são definidas na configuração!

## Comandos
|Comando         |Descrição                      |Permissão                    |
|----------------|-------------------------------|-----------------------------|
|/leaf        |Mostrará como utilizar o comando |`OP ou *`           |
|/leaf reload    |Recarregará as configurações dos plugins Leaf |`OP ou *`       |
|/leaf plugins    |Verá a lista de plugins Leaf no servidor |`OP ou *`       |

## Configuração
```yml
#
# Todos os direitos reservados a Leaf Code;
#
# Este plugin é responsável pelo funcionamento de outros plugins da Leaf Code!
# Utilize com carinho o nosso trabalho ♥, lembre-se de dar sugestões em nosso Discord!
#
# GitHub: https://github.com/leafcodebr
# Nosso Discord sempre estará vinculado ao GitHub!
#
Database: MongoDB

Databases:
  MySQL:
    url-login: ""
  MongoDB:
    url-login: ""
Opcoes:
  Notify-updates : true
# Servidor: Você poderá utilizar estas informações nas configurações de texto dos plugins LeafCode.
Servidor:
  # Utilize %leaf_nome% para usar esta informação.
  Nome: "LeafMC"
  # Utilize %leaf_prefix% para usar esta informação.
  Prefix: "&5&lLeaf&f&lMC"
  # Utilize %leaf_site% para usar esta informação.
  Site: "www.github.com/leafcodebr"
  # Utilize %leaf_discord% para usar esta informação.
  Discord: "www.github.com/leafcodebr"
  # Utilize %leaf_forum% para usar esta informação.
  Forum: "www.github.com/leafcodebr"
  # Utilize %leaf_loja% para usar esta informação
  Loja: "www.github.com/leafcodebr"
Mensagens:
  Comandos:
    sem_permissao:
      - "&cVocê não tem permissão para utilizar este comando!"
    target_player:
      - "&cVocê não pode utilizar este comando em si mesmo!"
#Auto-broadcast: Mensagens que serão enviadas no chat automaticamente.
Auto-broadcast:
  # Enable: 'true' para ativar e 'false' para desativar.
  enable: false
  # Delay: O atraso para enviar a mensagem.
  delay: 30
  # Som: Quando a mensagem for enviada, tocará um som (Deixe vazio para desativar)
  som: "WOOD_CLICK"
  mensagens:
    - "%leaf_prefix% &fCompre VIP em nossa loja: &5%leaf_loja%&f!"
    - "%leaf_prefix% &fEntre em nosso discord! &5%leaf_discord%&f!"
    - "%leaf_prefix% &fAcesse o nosso fórum: &5%leaf_forum%&f!"
    - "%leaf_prefix% &fAcesse o nosso site: &5%leaf_site%&f!"
```
![configurado](https://cdn.discordapp.com/attachments/967197530351865886/969379853801488494/unknown.png)
![configurado](https://cdn.discordapp.com/attachments/967197530351865886/969372560284348436/cmd_lDKnBlG8NA.png)
![configurado](https://cdn.discordapp.com/attachments/967492304984244264/969372929345347624/javaw_2bUvcSUMLf.png)
![configurado](https://cdn.discordapp.com/attachments/967492304984244264/969372929555058719/cmd_dKSZIuXzQ1.png)
