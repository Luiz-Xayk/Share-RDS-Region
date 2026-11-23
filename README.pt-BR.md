🇺🇸 [English](README.md) | 🇧🇷 [Português](README.pt-BR.md)

# Share-RDS-account-region

Passo a passo para compartilhar snapshots do Amazon RDS com outras contas AWS e copiá-los para outras regiões.

## Criação e Compartilhamento do Snapshot entre Contas

- No painel do RDS, vá para **Snapshots** e clique em **Take snapshot**.
- Selecione o snapshot gerado, clique em **Actions** e depois em **Share snapshot**. Defina como privado ou público e adicione o ID da conta para a qual deseja enviar o snapshot.
- Acesse a outra conta, vá em **Snapshots** e depois na aba **Shared with me**. Clique em **Actions** e depois em **Restore snapshot**.

## Compartilhamento do Snapshot entre Regiões

- No painel do RDS, vá para **Snapshots** e clique em **Take snapshot**.
- Selecione o snapshot gerado, clique em **Actions** e depois em **Copy snapshot**. Dê um nome para o DB e selecione a região desejada.
- Após o status da cópia ficar como **Completed**, clique em **Actions** e depois em **Restore snapshot**.
