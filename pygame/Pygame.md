## Что такое Pygame?
Библиотека для создания игр и мультимедийных приложений на Python.  
**Ключевые возможности**: работа с графикой, звуком и вводом.
## Основные команды:
- **Инициализация**: `pygame.init()`.
- **Окно**:
```python
screen = pygame.display.set_mode((800, 600))
```
- **Игровой цикл**:
```python
while running:
	for event in pygame.event.get():
		if event.type == pygame.QUIT:
			running = False
```

## Полезные ссылки:

- [Официальный сайт](https://www.pygame.org)
- [[Игровой цикл]]
- [[Python]]