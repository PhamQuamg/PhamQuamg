```python
import pygame
import random
# Khởi tạo game
pygame.init()
# Màu sắc
BLACK = (0, 0, 0)
WHITE = (255, 255, 255)
GREEN = (0, 255, 0)
RED = (255, 0, 0)
# Cài đặt kích thước cửa sổ
SCREEN_WIDTH = 800
SCREEN_HEIGHT = 600
screen = pygame.display.set_mode((SCREEN_WIDTH, SCREEN_HEIGHT))
# Tiêu đề cửa sổ
pygame.display.set_caption("Rắn săn mồi")
# Điểm số
font = pygame.font.Font(None, 36)
score = 0
# Khởi tạo rắn
snake_block_size = 10
snake_speed = 15
snake_list = []
snake_length = 1
# Hướng di chuyển
direction = "right"
# Tạo mồi
food_block_size 
