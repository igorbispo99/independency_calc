
<img width="1280" height="640" alt="capa-independencia-financeira" src="https://github.com/user-attachments/assets/6f96dff2-ec57-4319-90e4-a84c99748621" />

# 📈 Simulador de Independência Financeira

Uma aplicação web interativa e de ficheiro único (single-file) desenhada para ajudar a calcular e visualizar a sua jornada rumo à independência financeira.
Este simulador responde à pergunta fundamental: "Em quanto tempo a minha renda passiva se igualará à minha renda ativa, assumindo que poupo X% do meu salário todos os meses?"

## ✨ Funcionalidades

- Cálculo Realista: Utiliza a Taxa Real de rentabilidade (descontando a inflação anual do rendimento do CDI) para garantir que as projeções mantêm o poder de compra no futuro.
- Ajuste Dinâmico (Slider): Altere a sua taxa de poupança mensal (de 1% a 100%) através de um controlo deslizante e veja os resultados atualizarem instantaneamente.
- Gráfico SVG Customizado: Visualização clara da evolução do património e da curva de crescimento da renda passiva até cruzar a linha da renda ativa, tudo gerado nativamente sem necessidade de bibliotecas de gráficos externas pesadas.

Design Responsivo: Interface moderna, limpa e responsiva, otimizada para computadores, tablets e telemóveis.

## 🚀 Tecnologias Utilizadas

O projeto foi construído com foco na simplicidade de implementação (zero build-step):

- React 18: Importado diretamente via CDN.
- Tailwind CSS: Para estilização rápida e responsiva via CDN.
- Babel Standalone: Para compilar o código JSX diretamente no navegador.
- Lucide Icons (SVG Inline): Ícones integrados diretamente no código para evitar dependências externas.

## 🛠️ Como Usar (Instalação)

Sendo um projeto "Zero-Config" contido num único ficheiro, não precisa de instalar o Node.js, Webpack ou qualquer outro gestor de pacotes.

- Faça o clone do repositório:
```
git clone https://github.com/igorbispo99/independency_calc.git
```

- Navegue até à pasta do projeto.
- Dê um duplo clique no ficheiro index.html para abri-lo no seu navegador web preferido.

## 🌐 Hosting (GitHub Pages)

Este projeto está perfeitamente otimizado para o GitHub Pages. Para publicá-lo:

- Faça o upload do index.html para a branch principal (ex: main) do seu repositório.
- Vá a Settings > Pages no GitHub.
- Em Source, selecione Deploy from a branch e escolha a branch main.

Guarde. Em poucos minutos, o seu simulador estará disponível online!

Desenvolvido para fins educativos e de planeamento financeiro pessoal.
