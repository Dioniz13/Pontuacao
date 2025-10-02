# 🎯 Verificador de Pontuação

Um programa simples em JavaScript que verifica se a pontuação do usuário é suficiente para vencer.

## ✨ Funcionalidades

- Interface interativa com o usuário
- Verificação de pontuação mínima para vitória
- Feedback imediato baseado na pontuação
- Execução direta no navegador

## 🚀 Como Usar

### Método 1: Clonando o repositório
```bash
git clone https://github.com/seu-usuario/verificador-pontuacao.git
```

Abra o arquivo index.html no seu navegador

### Método 2: Execução direta
Crie um arquivo HTML com o seguinte código:
```
html
<!DOCTYPE html>
<html>
<head>
    <title>Verificador de Pontuação</title>
</head>
<body>
    <script src="script.js"></script>
</body>
</html>
```

## 💻 Código
### script.js
```javascript
let pontuação = prompt("Digite sua pontuação:");
if (pontuação >= 1000) {
    alert("Parabéns, você venceu!");
} else {
    alert("Tente novamente para ganhar.");
}
```

## 🎯 Exemplos de Funcionamento

* Entrada: "100" → Saída: "Parabéns, você venceu!"

* Entrada: "150" → Saída: "Parabéns, você venceu!"

* Entrada: "99" → Saída: "Tente novamente para ganhar."

* Entrada: "50" → Saída: "Tente novamente para ganhar."

* Entrada: "0" → Saída: "Tente novamente para ganhar."

## 🔍 Lógica do Programa
1. Coleta de dados: O programa solicita uma pontuação ao usuário via prompt()

2. Verificação:

* Se pontuação ≥ 1000 → "Parabéns, você venceu!"

* Se pontuação < 1000 → "Tente novamente para ganhar."

## ⚠️ Características
* Pontuação mínima para vencer: 1000 pontos

* Conversão automática: JavaScript converte automaticamente a entrada string para número na comparação

* Feedback claro: Mensagens diretas indicando sucesso ou necessidade de nova tentativa

## 🛠️ Tecnologias Utilizadas
* HTML5

* JavaScript Vanilla

* Funções nativas do navegador (prompt, alert)

## 📁 Estrutura do Projeto
```text
verificador-pontuacao/
│
├── index.html          # Arquivo HTML principal
├── script.js           # Arquivo JavaScript com a lógica
└── README.md           # Documentação
```

## 🎮 Possíveis Melhorias Futuras

* Adicionar diferentes níveis de dificuldade

* Implementar sistema de ranking

*Adicionar validação de entrada (apenas números)

*Criar interface visual mais elaborada

## 🤝 Contribuindo
### Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto

2. Crie uma Branch para sua feature (git checkout -b feature/AmazingFeature)

3. Commit suas mudanças (git commit -m 'Add some AmazingFeature')

4. Push para a Branch (git push origin feature/AmazingFeature)

5. Abra um Pull Request



## ⭐ Se este projeto foi útil, deixe uma estrela no repositório!
