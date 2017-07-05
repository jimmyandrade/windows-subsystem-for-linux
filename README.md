# Configurando o Subsistema do Windows para Linux

## Etapa 1 - Ative o modo de desenvolvedor
1. Acesse as configurações do Windows e informe "desenvolvedor" na busca;
2. Clique em "Modo de desenvolvedor" na seção "Usar recursos de desenvolvedor";
3. Confirme a mensagem de segurança;
4. O Windows começará a instalar o pacote do Modo de Desenvolvedor;

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
