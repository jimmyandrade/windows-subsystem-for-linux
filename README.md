# Configurando o Subsistema do Windows para Linux

## Etapa 1 - Ative o modo de desenvolvedor
1. Utilize o menu **Iniciar** para acessar as **Configurações** do Windows;
2. Em **Localizar uma configuração**, informe "desenvolvedor" na busca;
3. Selecione **Usar recursos de desenvolvedor**;
4. Clique em **Modo de desenvolvedor** na seção **Usar recursos de desenvolvedor**;
5. Se surgir alguma mensagem de segurança, confirme;
6. O Windows começará a instalar o pacote do Modo de Desenvolvedor. Você verá a mensagem **Instalando o pacote do Modo de Desenvolvedor**;
7. Aguarde até que a instalação seja finalizada.

## Etapa 2 - Instale o Windows Subsystem for Linux
1. Utilize o menu **Iniciar** para localizar o **PowerShell**;
2. Clique com o botão direito em **PowerShell** e selecione **Executar como administrador**;
3. Execute o comando `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`.
4. Você receberá a mensagem de confirmação "Você deseja reiniciar o computador para concluir esta operação agora?". Digite Y;
5. O computador reiniciará;

### Alternativa - Instalando via Painel de Controle
1. Vá ao Painel de Controle > Programas e Recursos > Recursos do Windows;
2. Marque Windows Subsystem for Linux (Subsistema do Linux para Windows) se não estiver marcado;
3. O computador reiniciará e exibirá a mensagem **Instalando recursos**;

## Etapa 3 - Instale o bash do Ubuntu
1. Utilize o menu iniciar para abrir o **PowerShell**;
2. Digite `bash`;
3. As próximas instruções dependerão dos cenários abaixo:

### Cenário 1

Se você ver a seguinte mensagem:

```shell
-- Beta feature --
Isso instalará o Ubuntu no Windows, distribuído pela Canonical
e licenciado sob os termos disponíveis aqui:
https://aka.ms/uowterms
```

1. Confirme a instalação com "y". O Ubuntu começará a ser baixado da Windows Store;
2. Se solicitado um locale padrão, mantenha en_US;
3. Informe o nome de usuário UNIX e informe uma senha.

### Cenário 2

Se você ver a seguinte mensagem:

```shell
O Subsistema do Windows para Linux não tem distribuições instaladas.
As distribuições podem ser instaladas visitando a Microsoft Store:
https://aka.ms/wslstore
Pressione qualquer tecla para continuar...
```

1. Em seu navegador de preferência, acesse https://aka.ms/wslstore;
2. Escolha um sistema operacional de sua preferência (**Ubuntu** é recomendado);
3. Clique em **Obter** ou **Instalar** e aguarde alguns instantes.

