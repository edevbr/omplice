# Omplice

App de computador do [omp](https://github.com/can1357/oh-my-pi): conversas com o agente, área de código e celular conectado.

Este repositório guarda só as **versões compiladas** do Omplice. O código-fonte não fica aqui.

## Baixar

Abra o [último lançamento](../../releases/latest) e baixe o arquivo do seu sistema:

| Sistema | Arquivo |
| --- | --- |
| Windows 10/11 (x64) | `Omplice_<versão>_x64-setup.exe` (instalador) |
| Linux (x86_64) | `Omplice_<versão>_amd64.AppImage` |

No Windows, rode o instalador. Ele instala só para o seu usuário, cria o atalho e, se faltar, instala o WebView2. O instalador ainda não tem assinatura de código da Microsoft, então o SmartScreen pode avisar na primeira vez: clique em **Mais informações → Executar assim mesmo**.

No Linux:

```sh
chmod +x Omplice_*_amd64.AppImage
./Omplice_*_amd64.AppImage
```

## Atualizações

Depois de instalado, o Omplice confere sozinho se há versão nova, baixa e verifica a assinatura. A versão nova entra na próxima vez que o app abrir; no Windows, o instalador novo roda sozinho, mostrando só uma barra de progresso. Para ver ou forçar a checagem, abra **Configurações → Atualizações**.

Cada versão é assinada: o app só instala um pacote cuja assinatura (`.sig`) confere com a chave de lançamento.

## Onde as versões são publicadas

- Gitea: <https://git.evandro.dev.br/evandro/omplice/releases> (o que os apps instalados leem)
- GitHub: <https://github.com/edevbr/omplice/releases> (espelho)

Os dois recebem os mesmos arquivos, publicados automaticamente a cada versão nova.
