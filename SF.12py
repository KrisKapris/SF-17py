ticket_number = int(input("Пожалуйста введите нужное количество билетов"))  # запрос количества билетов

price_all = int(0)  # объявление переменной для подсчета суммы

for i in range(ticket_number):
     i += 1
     age_for_ticket = int(input(f'Для какого возраста билет № {i}: '))

     if age_for_ticket < 18:
         print('Билет бесплатный')

     elif 25 > age_for_ticket >= 18:
         price_all += 990
         print('Стоимость билета: 990 руб.')

     else:
         price_all += 1390
         print('Стоимость билета: 1390 руб.')

if ticket_number > 3:  # если количество билетов больше 3 то применяется скидка
    price_all = price_all - ((price_all / 100) * 10)
    print(f'Сумма к оплате {price_all} руб. с учетом 10%-ой скидки на полную стоимость заказа за регистрацию 3-х человек')
else:
    print(f'Сумма к оплате {price_all} руб.')


