# slovo-tot
Сила русского слова-кода. Кириллические инструменты для разработки. 🔮
## Пример  
```python  
from main import магический_старт  
магический_старт()  # Вывод: "Привет от Тота! 🌌 Этот код написан на кириллице." 
# tests/test_main.py  
from main import магический_старт  

def test_магический_старт(capsys):  
    магический_старт()  
    captured = capsys.readouterr()  
    assert "Привет от Тота!" in captured.out  
