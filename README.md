# Configurando o Subsistema do Windows para Linux

## Etapa 1 - Ative o modo de desenvolvedor
1. Utilize o menu **Iniciar** para acessar as **Configurações** do Windows;
2. Em **Localizar uma configuração**, informe "desenvolvedor" na busca;
3. Selecione **Usar recursos de desenvolvedor**;
4. Clique em **Modo de desenvolvedor** na seção **Usar recursos de desenvolvedor**;
5. Se surgir alguma mensagem de segurança, confirme;
6. O Windows começará a instalar o pacote do Modo de Desenvolvedor. Você verá a mensagem **Instalando o pacote do Modo de Desenvolvedor**;
7. Aguarde até que a instalação seja finalizada.

## Etapa 2 - Verifique se o Windows Subsystem for Linux está instalado
1. Vá ao Painel de Controle > Programas e Recursos > Recursos do Windows;
2. Marque Windows Subsystem for Linux (Subsistema do Linux para Windows) se não estiver marcado;
3. O computador reiniciará;

## Etapa 3 - Instale o bash do Ubuntu
1. Abra o prompt de comando e digite `bash`.
   Provavelmente você verá a seguinte mensagem:

```shell
-- Beta feature --
Isso instalará o Ubuntu no Windows, distribuído pela Canonical
e licenciado sob os termos disponíveis aqui:
https://aka.ms/uowterms
```

2. Confirme a instalação com "y". O Ubuntu começará a ser baixado da Windows Store;
3. Se solicitado um locale padrão, mantenha en_US;
4. Informe o nome de usuário UNIX e informe uma senha.
