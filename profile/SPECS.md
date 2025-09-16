# 📜 Descrição do Servidor — **Muximba**

**Muximba** é um **OT Server Global** inspirado no Tibia oficial, com suporte às versões mais recentes (13.x) e foco total em **estabilidade, uptime e experiência imersiva**.
Nosso nome vem de uma palavra de origem Bantu que significa **coração**, representando a essência da comunidade que queremos criar: um lugar onde o jogador se sente em casa e faz parte de algo maior.

---

## 🎯 Objetivo

Criar um ambiente global, confiável e divertido para jogadores veteranos e novatos, com infraestrutura moderna e totalmente automatizada. Nosso servidor roda em **containers Docker** e utiliza **pipelines shell-first** para garantir builds reproduzíveis, deploys consistentes e manutenção simplificada — tudo versionado no nosso monorepo privado.

---

## 🛠️ Infraestrutura Técnica

* **Base do Servidor:** Canary (OpenTibiaBR) + datapack OTServBR-Global (compatível 13.x)
* **Banco de Dados:** MariaDB 11, com initdb versionado
* **Ambiente de Desenvolvimento:** Docker Compose + scripts shell para build, seed e smoke tests
* **CI/CD:** preparado para GitHub Actions gerar imagens e binários automaticamente
* **Cliente:** OTClientV8 (build Linux via Docker incluído)
* **Site:** landing page em Nginx, pronta para personalização e status do servidor
* **Configurações versionadas:** `config.lua` em template, carregado via variáveis de ambiente

---

## 🌍 Características de Jogo

* **Mundo Global:** mapas, NPCs, monstros e quests atualizados para a versão 13.x
* **Rates balanceados:** XP, loot e skills configuráveis via staging
* **Eventos recorrentes:** preparados para engajar a comunidade (raids, bosses, boosts)
* **Sistema de Loja e VIP:** baseado em datapack global, pronto para personalização
* **Compatibilidade total com client customizado:** suporte para novos outfits, sprites e features

---

## 🔐 Estabilidade e Segurança

* **Uptime planejado >99,5%** — redundância e failover incluídos no roadmap
* **Backups diários automáticos** de banco e world, com teste de restauração
* **Proteção contra exploits e anti-DDoS** via infraestrutura dedicada
* **Monitoramento ativo** de performance, logs centralizados e alertas

---

## 💬 Comunidade

O coração do Muximba está na comunidade. Queremos unir jogadores do Brasil, América Latina e além em um ambiente saudável, com regras claras e moderação ativa. Nosso Discord e redes sociais são parte essencial da experiência.

---

## ✨ Identidade Visual

Nosso logo — inspirado em um mago sábio, reminiscente de Gandalf, emoldurado em um selo dourado — reforça o tema de sabedoria, aventura e mistério que define o mundo de Muximba.

---

Quer que eu gere também uma **descrição curta para o site** e outra **para divulgar no Discord/Facebook/Reddit** (anúncio de lançamento)? Isso ajuda a manter comunicação consistente e pronta para marketing.
