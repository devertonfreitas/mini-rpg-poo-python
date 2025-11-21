📦 Mini RPG em Python — Paradigma de POO

Um mini-sistema de RPG desenvolvido em Python para estudar e aplicar os principais conceitos de Programação Orientada a Objetos.
O projeto simula heróis, monstros, habilidades, itens e batalhas em turnos — tudo estruturado de forma modular, limpa e expansível.

🚀 Funcionalidades Principais

Criação de personagens (Guerreiro, Mago, Arqueiro)

Classe base com herança e polimorfismo

Armas, poções e inventário

Sistema de habilidades especiais

Monstros com comportamentos próprios (Goblin e Orc crítico)

Rolagem de dados para variação de dano

Combate 1x1 e batalhas em equipe

Execução demonstrativa via main()

🧠 Conceitos de POO Aplicados

Herança — Personagens e monstros derivados de uma classe base

Polimorfismo — Ataques e habilidades com comportamentos diferentes

Encapsulamento — Vida protegida via propriedades

Composição — Inventário, armas e habilidades acoplados ao personagem

Classes Abstratas — Modelo para habilidades

Métodos Estáticos — Dado para aleatoriedade

📂 Estrutura do Projeto
📁 mini-rpg-poo-python
 ┣ 📄 rpg.py
 ┗ 📄 README.md

▶️ Como Executar

Certifique-se de ter o Python instalado.

python rpg.py


A função main() já executa:

criação dos heróis

equipamento de armas

uso de poções

habilidades especiais

duelo contra Goblin

batalha em equipe contra Orc

🧱 Componentes do Sistema
🧍 Personagens

Guerreiro — foco em força física

Mago — ataque baseado em poder mágico

Arqueiro — precisão influencia o dano

👹 Monstros

Goblin (via método fábrica)

Orc — golpe crítico com chance aleatória

🗡️ Itens

Arma — aumenta poder de ataque

Poção de Vida — restaura HP

Inventário — armazena itens

🔥 Habilidades

AtaqueForte

BolaDeFogo

🎲 Sistema de Batalha

Turnos alternados

Variação aleatória de dano

Identificação automática do vencedor

Suporte a equipes

🌱 Possíveis Melhorias

Sistema de níveis e experiência

Novos tipos de armas e itens raros

Barra de status visual

Log de batalha mais completo

Versão em interface gráfica

📜 Licença

Este projeto é de uso acadêmico e livre para estudo.
