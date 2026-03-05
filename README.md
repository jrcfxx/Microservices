# Microservices

Este repositório foi criado para reunir uma visão introdutória sobre **arquitetura de microservices** e apoiar estudos sobre o tema.

## O que são microservices?

Microservices (ou microsserviços) são um estilo arquitetural no qual uma aplicação é dividida em serviços menores, independentes e focados em capacidades específicas do negócio.  
Cada serviço possui responsabilidade bem definida, pode ser desenvolvido de forma isolada e, em muitos casos, implantado separadamente.

Em vez de um único sistema monolítico concentrando todas as funcionalidades, a solução passa a ser composta por vários serviços que se comunicam entre si por APIs ou mensageria.

## Para que servem?

A abordagem de microservices é útil para:

- **Escalar partes específicas do sistema** sem escalar tudo ao mesmo tempo.
- **Aumentar a autonomia de times**, permitindo entregas paralelas.
- **Facilitar evolução contínua** de funcionalidades com menor acoplamento.
- **Melhorar resiliência**, reduzindo impacto de falhas generalizadas.

## Benefícios principais

- **Deploy independente** por serviço.
- **Maior alinhamento com domínio de negócio** (cada serviço representa uma capacidade).
- **Flexibilidade tecnológica** (quando bem governada).
- **Maior velocidade de entrega** em equipes maduras.

## Desafios e cuidados

Apesar das vantagens, microservices também trazem complexidade:

- Comunicação distribuída e latência de rede.
- Observabilidade mais difícil (logs, métricas e rastreamento).
- Gerenciamento de dados entre múltiplos serviços.
- Necessidade de automação robusta (CI/CD, testes, monitoramento).
- Custos operacionais maiores se comparados a soluções mais simples.

Por isso, microservices **não são solução universal**. Em muitos cenários, um monólito modular é a melhor escolha inicial.

## Quando faz sentido adotar?

Geralmente, a adoção de microservices faz mais sentido quando:

- O sistema já possui escala e complexidade crescentes.
- Existem múltiplas equipes atuando no mesmo produto.
- Há maturidade em práticas de DevOps e observabilidade.
- O domínio de negócio está relativamente estável para permitir boa decomposição.

## Contexto deste repositório

O conteúdo deste repositório foi contextualizado a partir do artigo clássico:

- **FOWLER, Martin; LEWIS, James. _Microservices_.**  
  Disponível em: <https://martinfowler.com/articles/microservices.html>
