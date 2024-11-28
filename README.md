# 📎 Encurtador de URLs  

Este projeto é um encurtador de URLs desenvolvido em **Java**. Ele gera um UUID único para cada URL encurtada, permitindo acesso à URL original por meio desse identificador. Além disso, armazena a URL original e seu tempo de expiração no **AWS S3**.  

O projeto está implantado e em execução no **AWS Lambda**, garantindo alta escalabilidade e baixo custo operacional.  

## 🚀 Funcionalidades  

- **Encurtamento de URLs**: Gera um UUID para acesso à URL original.  
- **Armazenamento**: Salva a URL original e o tempo de expiração no bucket do **AWS S3**.  
- **Execução Serverless**: Utiliza o **AWS Lambda** para execução das funções, garantindo eficiência e escalabilidade.  

## 🛠️ Tecnologias Utilizadas  

- **Java**: Linguagem principal do projeto.  
- **AWS Lambda**: Para execução do código em ambiente serverless.  
- **AWS S3**: Para armazenamento das URLs originais e seus tempos de expiração.  
