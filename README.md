# L37-1

1. Будуємо модель поліноміальної регресії та візуалізуємо результати за допомогою matplotlib.pyplot.
2. Спочатку імпортуємо датасет та розділяєм на ознаки і цільову змінну.
3. Використовуючи клас PolynomialFeatures, ознаки X трансформуєм в поліноміальні ознаки X_poly.
4. Параметр degree вказує степінь поліноміальних ознак, в даному випадку degree=4.
5. Створюєм об'єкт моделі лінійної регресії і викликаємо метод fit, який навчає модель на даних X_poly та y.
6. Тепер виконуємо передбачення цільових змінних за допомогою методу predict та зберігаєм в змінну y_poly_pred.
7. Візуалізуємо результати моделі на графіку, використовуючи метод scatter для відображення даних та метод plot для відображення поліноміальної регресії.
8. І виводим значення коефіцієнту детермінації (R-squared) за допомогою методу score моделі.

#37-2 (в коментарях)
