# Инструкция по добавлению фото в проекты

## Как добавить фото к каждому проекту

В файле `project.html` найдите блок проекта и обновите атрибут `style` в div с классом `project-image`.

### Пример:

Текущая структура:
```html
<div class="project-image" style="background-image: url(''); background-color: linear-gradient(135deg, #667eea 0%, #764ba2 100%); background-size: cover; background-position: center;">
  <p>QODEX</p>
</div>
```

**Замените пустую строку в `url('')` на путь к вашему фото:**

```html
<div class="project-image" style="background-image: url('путь/к/вашему/фото.jpg'); background-color: linear-gradient(135deg, #667eea 0%, #764ba2 100%); background-size: cover; background-position: center;">
  <p>QODEX</p>
</div>
```

### Варианты путей:

1. **Если фото в папке `photo/`:**
   ```html
   style="background-image: url('../photo/qodex.jpg'); ..."
   ```

2. **Если фото в той же папке `projects/`:**
   ```html
   style="background-image: url('qodex.jpg'); ..."
   ```

3. **Онлайн URL:**
   ```html
   style="background-image: url('https://example.com/photo.jpg'); ..."
   ```

### Все проекты для обновления:

1. **QODEX** - Math Courses
2. **OIMO** - OIMO Technology
3. **Chuprina** - Chuprina Partners
4. **Lina Beauty** - Lina Beauty
5. **School News** - School News Account
6. **Manas Ulu** - Manas Ulu
7. **Guidebook** - Guidebook for Foreign Travelers

### Рекомендации:

- **Размер фото:** 400x300px или больше (минимум)
- **Формат:** JPG, PNG, WebP
- **Качество:** Оптимизируйте фото для веба (не более 500KB)
- **Пропорции:** Горизонтальное соотношение (примерно 4:3 или 16:9)

### Как фото будут отображаться:

- Фото автоматически масштабируется и центрируется
- Если фото не загружается, будет виден цветной градиент как подложка
- Текст с названием проекта остается видимым сверху фото

---

**Если у вас возникли вопросы, просто вставьте URL фото в соответствующую строку!**
