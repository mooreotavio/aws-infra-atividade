# Configuração de Infraestrutura AWS

## Passos Realizados
1. **Security Groups**: 
   - Criação do grupo EC2-SG: Liberou SSH (porta 22) para IP pessoal e HTTPS (porta 80) público.
   - Criação do grupo RDS-SG: Liberou PostgreSQL (5432) apenas para EC2-SG.
2. **EC2**: Criada Instância Amazon Linux (free tier) com Security Group EC2-SG e gerado par de chaves .pem.
3. **RDS**: Criado Banco PostgreSQL (free tier) com Security Group RDS-SG, sem acesso público, usuário 'otavio' e nome 'meubanco', além de senha de acesso.

## Screenshots
- ![Security Groups](https://github.com/user-attachments/assets/e9e07c95-10b0-490d-bd1c-451848d407af)
- ![Security Groups](https://github.com/user-attachments/assets/1714d44b-3ad6-4f01-9400-ca83e929e3f5)
- ![EC2 Instance](https://github.com/user-attachments/assets/12d714d2-b11f-45b7-874c-765154b0ae4f)
- ![EC2 Instance](https://github.com/user-attachments/assets/26009f2f-0229-40dc-8297-3ebc25260822)
- ![RDS Endpoint](https://github.com/user-attachments/assets/ce9b25d1-8ec6-4804-87cd-210789f7efb2)
