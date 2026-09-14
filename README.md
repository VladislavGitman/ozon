# ozon

ШАГ 3/4: Ищем и при необходимости нажимаем кнопку 'Войти'...
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[normalize-space(.)='Войти']'
Кнопка входа успешно найдена по By.xpath: '//div[normalize-space(.)='Войти']'
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[.//span[normalize-space(.)='Войти']]'
Кнопка входа успешно найдена по By.xpath: '//div[.//span[normalize-space(.)='Войти']]'
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[normalize-space(.)='Войти' and contains(@class,'q6v_36')]'
Не удалось найти кнопку входа по By.xpath '//div[normalize-space(.)='Войти' and contains(@class,'q6v_36')]'. Пробуем следующий метод...
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[contains(@class,'q6v_36') and normalize-space(text())='Войти']'
Не удалось найти кнопку входа по By.xpath '//div[contains(@class,'q6v_36') and normalize-space(text())='Войти']'. Пробуем следующий метод...
Попытка найти кнопку входа с помощью By.css selector и локатора: 'div.q6v_36'
Не удалось найти кнопку входа по By.css selector 'div.q6v_36'. Пробуем следующий метод...
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[normalize-space(.)='Войти' and (contains(@role,'button') or @onclick)]'
Не удалось найти кнопку входа по By.xpath '//div[normalize-space(.)='Войти' and (contains(@role,'button') or @onclick)]'. Пробуем следующий метод...
Попытка найти кнопку входа с помощью By.xpath и локатора: '//div[normalize-space(.)='Войти']'
Кнопка входа успешно найдена по By.xpath: '//div[normalize-space(.)='Войти']'
Попытка найти кнопку входа с помощью By.xpath и локатора: '//*[contains(@class,'button') and normalize-space(.)='Войти']'
Не удалось найти кнопку входа по By.xpath '//*[contains(@class,'button') and normalize-space(.)='Войти']'. Пробуем следующий метод...

--- ВЫВОД ИНФОРМАЦИИ ОБ Кнопка 'Войти' ---
  Тег HTML: div
  Видимый текст: 'Войти'
  ID атрибут: ''
  Класс атрибут: 'v5n_30'
  Имя (name) атрибут: 'None'
  Value (значение) атрибут: 'None'
  HREF (для ссылок) атрибут: 'None'
  Атрибут data-test-id (если есть): 'None'
  Элемент доступен (кликабелен): True
  Элемент виден на странице: True
  Элемент выбран (для чекбоксов/радиокнопок): False
  Размер (ширина, высота): {'height': 44, 'width': 76}
  Позиция (X, Y): {'x': 1084, 'y': 16}
  XPath (сгенерированный): id("stickyHeader")/DIV[1]/DIV[4]/DIV[1]
  CSS Selector (сгенерированный): html>body:nth-child(2)>div#__ozon>div#layoutPage.a0.a1>div.b6:nth-child(1)>div.uw_a2q:nth-child(1)>div>header.uw_a1i>div#stickyHeader.uw_ai>div.uw_ia.uw_a0i>div.uw_a9h:nth-child(4)>div.v5n_30:nth-child(1)
-------------------------------------------------
Кнопка 'Войти' успешно нажата.
