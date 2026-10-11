# Linux Web PC

Cria um PC Linux temporário nos servidores do GitHub Actions, com área de trabalho XFCE e Google Chrome acessíveis pelo navegador.

## Como iniciar

1. Vá em **Actions → Linux Web PC → Run workflow**.
2. Defina um **usuário** e uma **senha**.
3. Inicie o workflow.
4. Abra a execução e copie o link `https://...trycloudflare.com`.
5. Abra o link, entre com o usuário e senha definidos.
6. No noVNC, clique em **Connect** e digite novamente a mesma senha.

## O que você verá

- Área de trabalho XFCE
- Google Chrome
- Terminal XFCE
- Gerenciador de arquivos
- Acesso `sudo`
- `neofetch`
- `tmate`

## Segurança

- Use senha forte.
- O link do Cloudflare é temporário, mas quem tiver o link e a senha poderá usar o PC.
- Não coloque credenciais sensíveis dentro da máquina.
- O GitHub cancela automaticamente jobs hospedados após 6 horas.
