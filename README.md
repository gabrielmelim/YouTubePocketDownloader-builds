# YouTubePocketDownloader (Builds)

Repositório público apenas para distribuição do executável do **YouTubePocketDownloader**.

> **Atenção:** Este repositório contém somente os arquivos de instalação (EXE/ZIP).
> O código-fonte do projeto não é público.

---

## O que é

YouTubePocketDownloader é um aplicativo desktop para **Windows** que permite:

- Baixar vídeos do YouTube em:
  - **WEBM Original (sem conversão)**
  - **MP4 (converter)**
  - **MP3 (converter)**
- Limitar a qualidade do vídeo (1080p, 720p, 480p ou *default*).
- Gerenciar uma **fila de downloads** com botão **Parar Tudo**.
- Tratar erros comuns em **português** (internet, vídeo removido/privado, espaço em disco, etc.).

Também oferece suporte a vídeos com restrição de idade (+18) usando os **cookies do seu navegador** (Chrome, Edge ou Firefox).  
O aplicativo **não armazena sua senha**, apenas reutiliza a sessão já logada no navegador.

---

## Download

1. Acesse a aba **Releases** deste repositório.
2. Na última release, vá até a seção **Assets**.
3. Baixe o arquivo:
   - `.exe` diretamente **ou**
   - `.zip` contendo o executável.
   
  Para baixar o programa, verifique sempre a última versão disponível em **Releases**: <https://github.com/gabrielmelim/YouTubePocketDownloader-builds/releases>

---

## Como usar

1. Extraia o `.zip` (se aplicável) e execute `YouTubePocketDownloader.exe`.
2. Windows pode acionar um alerta ao software por não ter uma licença paga, entao basta permitir que tudo irá funcionar.
3. No campo **YouTube URL**, cole o link do vídeo ou playlist.
4. Em **Salvar em**, escolha a pasta onde os arquivos serão gravados.
5. Escolha:
   - A **resolução** (default/1080p/720p/480p) – somente para WEBM/MP4.
   - O **formato**:
     - WEBM Original (sem conversão)
     - MP4 (converter)
     - MP3 (converter)
6. Clique em **Baixar**:
   - O primeiro vídeo começa imediatamente.
   - Os próximos entram na **fila**, mostrada na interface.
7. Para interromper tudo, use o botão **Parar Tudo**:
   - Cancela o download atual, limpa a fila e remove arquivos temporários.

---

## Vídeos +18 (restrição de idade)

Alguns vídeos exigem que você esteja logado no YouTube:

- O aplicativo tenta usar os cookies do seu navegador (Chrome/Edge/Firefox).
- Se o YouTube pedir login, o programa:
  - Mostra um aviso explicando o passo a passo.
  - Oferece abrir o YouTube no navegador para você fazer login.
- Depois de logado no navegador, basta tentar o download novamente.

O app **não armazena credenciais**, apenas reutiliza a sessão já autenticada.

---

## Período de avaliação (trial)

- Esta é uma **versão de avaliação**, com prazo limitado.
- O prazo é contado a partir da **data de compilação** do executável.
- O aplicativo precisa de **conexão com a internet** para validar a avaliação.
- Após o fim do período de teste:
  - O app informa que o período expirou.
  - O executável deixa de funcionar.

---

## Requisitos

- **Sistema**: Windows 10 ou superior.
- **Internet**:
  - Necessária para validar a avaliação.
  - Necessária para acessar o YouTube e baixar os vídeos.
- **Opcional (recomendado)**:
  - Chrome, Edge ou Firefox instalados para melhor suporte a vídeos +18.
