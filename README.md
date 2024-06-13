# Share-RDS-account-region
Share RDS snapshot with other accounts and regions

# Criação e compartilhamento do snapshot entre contas:
- No painel do RDS vá para "Snapshots" e "Take snapshot".
- Selecione o snapshot que foi gerado, clique em "actions" e depois "share snapshot". Set para private ou public e adicione o ID da conta que deseja enviar o snapshot.
- Acesse a outra conta, vá "snapshots" e depois para a aba "shared with me". Clique em "actions" e "restore snapshot".

# Compartilhamento do snapshot entre região:
- No painel do RDS vá para "Snapshots" e "Take snapshot".
- Selecione o snapshot que foi gerado, clique em "actions" e depois "copy snapshot". De um nome para o DB e selecione a região desejada.
- Após o status da cópia ficar como "Completed", clique em "actions" e "restore snapshot".
