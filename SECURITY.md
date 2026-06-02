# Security Policy

Report security issues privately through Zervio Solutions support channels.

Do not open public issues containing credentials, tokens, infrastructure details, exploit steps, or private customer data.

## Protected data

The following must never be committed:

- API keys and tokens
- Passwords and private keys
- TLS certificates and certificate private keys
- `.env` files
- Database dumps and runtime data
- Customer information
- Backups and logs

If a secret is exposed, rotate it immediately and remove it from git history before continuing deployment work.
