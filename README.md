```markdown
# Rectangle and Square Class Implementation 🧱🟦

This project demonstrates the use of Object-Oriented Programming (OOP) concepts in Python by implementing two classes: `Rectangle` and `Square`.

## 📚 Features
- Create rectangles and squares with customizable dimensions.
- Calculate area, perimeter, and diagonal.
- Generate a text-based picture representation of the shape.
- Compare shapes and adjust their dimensions dynamically.
- Handle square-specific behavior by overriding rectangle methods.

## 🛠️ Technologies
- Python 3

## 📦 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/abdulsamad00529/polygon-area-project.git
   ```
2. Navigate into the project directory:
   ```bash
   cd polygon-area-project
   ```
3. Run the Python file:
   ```bash
   python main.py
   ```

## 🖼️ Example
```python
sq = Square(5)
print(sq)           # Square(side=5)

sq.set_width(8)
print(sq)           # Square(side=8)

rect = Rectangle(4, 6)
print(rect)         # Rectangle(width=4, height=6)

print(rect.get_area())       # 24
print(rect.get_picture())    # Draws a rectangle with '*'
```

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
```

