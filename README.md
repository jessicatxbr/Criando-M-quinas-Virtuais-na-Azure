# Criando Máquinas Virtuais na Azure

# ☁️ Criando Máquinas Virtuais na Azure

![Badge Status](https://img.shields.io/badge/Status-Concluído-%2304D361)
![Badge Plataforma](https://img.shields.io/badge/Ambiente-Azure-blue)
![Badge Gratuito](https://img.shields.io/badge/Camada-Gratuita-%23f7df1e)
![Badge Infra](https://img.shields.io/badge/Infraestrutura-IaC%20Opcional-%23f06292)

> Projeto criado como parte do desafio **Criando máquinas Virtuais na Azure**. A proposta foi utilizar os serviços da Microsoft Azure para configurar e provisionar uma máquina virtual funcional, usando os recursos da camada gratuita, com atenção à escolha de imagem, localização e compatibilidade.

---

## 🎯 Objetivo do Projeto

- Criar uma **máquina virtual no Azure** utilizando o portal web
- Escolher uma imagem compatível e um tamanho suportado pela região
- Corrigir erros comuns de incompatibilidade (localização, imagem e tamanho)
- Explorar as opções gratuitas oferecidas pelo Azure
- Documentar o processo e registrar aprendizados técnicos

---

## 🚀 Etapas Realizadas

- [x] Acesso ao portal do Azure
- [x] Criação de novo recurso → Máquina Virtual
- [x] Escolha de imagem compatível
- [x] Correção de erro de localização
- [x] Escolha de tamanho suportado na assinatura
- [x] Configuração de credenciais de acesso (nome de usuário, chave ou senha)
- [x] Inicialização e teste da VM com RDP (3389) e HTTP (80)

---

## 📌 Dicas Importantes

❗ **Erros comuns resolvidos durante o projeto:**

1. **Imagem não válida para a localização**  
   → Solução: selecionar outra imagem suportada pela região `brazilsouth`.

2. **Tamanho de VM não disponível para a assinatura**  
   → Solução: trocar o tamanho da VM para um modelo compatível.

3. **Problemas com geração de VM (Gen2)**  
   → Solução: ajustar manualmente o tipo de imagem suportada.

---

## 🖥️ Resultados

A máquina virtual foi provisionada com sucesso e está em execução. Os recursos foram alocados corretamente, respeitando os limites da camada gratuita.

✅ Acesso funcional via RDP / HTTP
✅ Custo estimado: **US$ 0,00 / mês** (dentro dos limites da camada gratuita)

---

## 🧠 Aprendizados

- Entendimento da compatibilidade entre imagem e região no Azure
- Familiarização com o processo de provisionamento manual via portal
- Diagnóstico de erros comuns de VM e suas soluções
- Noções básicas de administração de infraestrutura em nuvem

---

## 🛠️ Recursos e Referências

- [Portal do Azure](https://portal.azure.com/)
- [Documentação Oficial - VMs no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Camada Gratuita da Azure](https://azure.microsoft.com/pt-br/free)
