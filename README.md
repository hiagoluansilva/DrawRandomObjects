# Draw Random Objects — Formas Aleatórias em Java Swing

🇧🇷 **Português** | 🇺🇸 [English](#english)

---

## Português

Aplicação Java com interface gráfica Swing que desenha formas geométricas aleatórias (linhas, ovais, retângulos, triângulos) em um painel.

### O que faz
- Desenha formas geométricas aleatórias em um **JPanel** personalizado
- Formas disponíveis: `MyLine`, `MyOval`, `MyRectangle`, `MyTriangle`
- Herança de `MyShape` para polimorfismo de desenho
- Cada clique/refresh gera novas formas com posições e cores aleatórias

### Estrutura de classes
```
MyShape.java      # classe base abstrata
MyLine.java       # linha aleatória
MyOval.java       # oval/círculo aleatório
MyRectangle.java  # retângulo aleatório
MyTriangle.java   # triângulo aleatório
DrawPanel.java    # JPanel que renderiza as formas
TestDraw.java     # JFrame principal — ponto de entrada
```

### Como executar
```bash
javac *.java
java TestDraw
```

---

## English

Java Swing application that draws random geometric shapes (lines, ovals, rectangles, triangles) on a panel.

### What it does
- Draws random geometric shapes on a custom **JPanel**
- Available shapes: `MyLine`, `MyOval`, `MyRectangle`, `MyTriangle`
- Inherits from `MyShape` for polymorphic drawing
- Each click/refresh generates new shapes with random positions and colors

### Class structure
```
MyShape.java      # abstract base class
MyLine.java       # random line
MyOval.java       # random oval/circle
MyRectangle.java  # random rectangle
MyTriangle.java   # random triangle
DrawPanel.java    # JPanel that renders shapes
TestDraw.java     # main JFrame — entry point
```

### How to run
```bash
javac *.java
java TestDraw
```
