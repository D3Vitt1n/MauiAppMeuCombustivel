# ⛽ Calculadora Etanol vs Gasolina (.NET MAUI)

Aplicativo mobile desenvolvido em **.NET MAUI** que ajuda o usuário a descobrir, de forma rápida e prática, qual combustível compensa mais abastecer: **Etanol ou Gasolina**.

---

## 📌 Sobre o Projeto

Este aplicativo utiliza a regra mais comum no Brasil para calcular a melhor escolha:

> ✅ Se o preço do **etanol for até 70% do valor da gasolina**, então o etanol compensa.  
> ❌ Caso contrário, a gasolina é a melhor opção.

O objetivo do projeto foi praticar desenvolvimento mobile com **.NET MAUI**, aplicando lógica de negócio real do dia a dia.

---

## 📱 Funcionalidades

- Inserção do preço do etanol
- Inserção do preço da gasolina
- Cálculo automático da melhor opção
- Exibição clara e objetiva do resultado
- Interface simples e intuitiva

---

## 🧠 Regra de Cálculo

```csharp
if (precoEtanol <= precoGasolina * 0.7)
{
    resultado = "Etanol compensa!";
}
else
{
    resultado = "Gasolina compensa!";
}
```

---

## 🚀 Tecnologias Utilizadas

- .NET MAUI
- C#
- XAML
- Visual Studio 2022+

---

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Abra o projeto no **Visual Studio 2022** com suporte ao .NET MAUI.

3. Execute em:
   - Android Emulator
   - Dispositivo físico
   - Windows

---

## 🎯 Objetivo

Este projeto foi desenvolvido para:

- Praticar desenvolvimento mobile multiplataforma
- Aplicar lógica de negócio real
- Consolidar conhecimentos em C# e .NET MAUI
- Criar um aplicativo útil e funcional

---

## 👨‍💻 Autor

**Vitor Hugo Gaspar de Souza**

Desenvolvedor Fullstack  
Pós-graduado em Desenvolvimento Fullstack  

🔗 Conecte-se comigo no LinkedIn  
🔗 Veja outros projetos no GitHub  

---

⭐ Se gostou do projeto, deixe uma estrela!
