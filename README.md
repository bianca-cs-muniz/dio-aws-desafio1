# 📦 Backup com S3 + Lambda

![Desafio 1](Desafio1.png)

## 📌 Sobre o projeto

Neste projeto eu estruturei um fluxo simples de backup de arquivos feito pelo usuário.

A ideia foi entender, na prática, como criar uma estrutura de software utilizando serviços da AWS e como cada recurso funciona dentro desse processo.

---

## 🧠 Objetivo

- Entender o funcionamento do S3  
- Entender como o Lambda reage a eventos  
- Criar um fluxo simples de backup automático  
- Aprender arquitetura básica na AWS  


---

## ⚙️ Como funciona

1. O usuário envia um arquivo  
2. O arquivo é armazenado no S3 (bucket principal)  
3. O S3 dispara um evento ao detectar o novo arquivo  
4. O Lambda é acionado automaticamente  
5. O Lambda copia o arquivo para o bucket de backup  

---

## 💡 Motivação

Decidi criar uma estrutura simples para facilitar o entendimento.

Simplifiquei o papel de cada serviço para conseguir visualizar melhor como funciona o fluxo completo e como os recursos da AWS se conectam.

Esse projeto representa meu início prático com AWS e arquitetura de software.

---

## 🚀 Conclusão

Esse projeto ajudou a entender:

- Como eventos funcionam na AWS  
- Como automatizar processos  
- Como estruturar um fluxo real de backend  
- Conceitos básicos de arquitetura em nuvem  