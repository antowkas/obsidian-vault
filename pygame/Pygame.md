## Что такое Pygame?
- Библиотека для создания игр и мультимедийных приложений на Python.  
- **Ключевые возможности**: работа с графикой, звуком и вводом.
## Пример базовой реализации:
```python
# Импорт и инициализация pygame
import pygame
pygame.init()
# Создание экрана
screen = pygame.display.set_mode((800, 600))  # ширина: 800, высота: 600
pygame.display.set_caption("Моя игра")
# Часы для управлением временем в циклах
clock = pygame.time.Clock()
# Игровой цикл
running = True
while running:
    # Считывание событий
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False	
	# Сброс картинки каждый цикл
	screen.fill("black")

	# ВАША ОТРИСОВКА ТУТ

	# Отображие изменений на экране
    pygame.display.flip()
	# Установка лимита FPS на 60 кадров
	clock.tick(60)
pygame.quit()
```
## Полезные ссылки:
- [[Документация Pygame]]
- [[Игровой цикл]]
- [[Python3]]
