# SatsWallet Identity Vault

Backup permanente e **offsite** da mídia de identidade (ícone, GIF e som) de assets
Taproot **mintados** na SatsWallet.

- Cada arquivo é nomeado `<sha256>__<nome>` — content-addressed e verificável.
- O `sha256` (e o CID IPFS) de cada peça fica ancorado no **Bitcoin**, gravado no
  metadado do asset Taproot no momento do mint.
- Esta é a 3ª cópia (além do nó IPFS na VPS e do espelho no Mini-PC).

Só entram aqui assets **mintados**. Previews/testes nunca são enviados.
Nenhum dado sensível (chaves, .env, uploads de clientes) é versionado aqui.
