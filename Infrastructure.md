Since we like to be transparent about your information and where it lives, we've made a list of the cloud services we use and what we use them for.

In a perfect would we would be self-hosting everything but currently with my personal situation and the current state of Australian Internet, it is't very feasable to provide a reliable service.

| Service        | Usage                                                           |
| :------------- | :-------------------------------------------------------------- |
| AWS Cloudfront | Cache for S3                                                    |
| AWS S3         | Storage for uploaded files                                      |
| AWS SES        | Automated Emails (Account Verification, Password Reset, etc...) |
| Cloudflare     | DDoS Protection and DNS                                         |
| Namesilo       | Domain Registrar                                                |
| Hydra          | Database (PostgreSQL), [Relay](https://relay.dariox.club), Redis, [Uptime](https://uptime.kate.pet/status/dariox), and [Mastodon](https://dariox.club) |

## Server Specifications (Hydra)
- Intel i7-6700 @4GHz
- 48GB DDR4 RAM (Non-ECC)
- Asrock Z170 Extreme4
- NVIDIA GeForce GTX 1060 (Video Encoding)
- SilverStone ECS06 (6 Port SATA3 Controller)
- Storage
  - SKHynix HFM512GD3HX015N (512GB M.2 SSD, Boot Drive)
  - 9tb ZFS Pool (3x WD30EFZX, Media Storage)
  - Kingston UV400 480GB SSD (Docker Storage)
