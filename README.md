# AB_tests
В данном блоке представлены проекты по анализу результатов A/B-тестирования:
1. [AB test (grocery delivery app)](https://github.com/jkozyrkova/AB_tests/blob/main/AB%20test%20(grocery%20delivery%20app).ipynb) - анализ эффективности умной системы рекомендации товаров в приложении доставки.
Используемые библиотеки: pandas, seaborn, scipy.stats, numpy, bootstrap.
3. [AB test (online dating app)](https://github.com/jkozyrkova/AB_tests/blob/main/AB%20test%20(online%20dating%20app).ipynb) - анализ работы нового алгоритма для поиска наиболее подходящих анкет в приложении онлайн-знакомств.
Используемые библиотеки: pandas, seaborn, scipy.stats, chi2_contingency, chi2.
5. [AB test (pizza delivery app)](https://github.com/jkozyrkova/AB_tests/blob/main/AB%20test%20(pizza%20delivery%20app).ipynb) - анализ эффективности нового алгоритма распределения заказов по курьерам в приложении доставки пиццы.
Используемые библиотеки: pandas, seaborn, scipy.stats, numpy.
7. [AB test (new payment)](https://github.com/jkozyrkova/AB_tests/blob/main/AB_tests_new_payment.ipynb) - анализ работы новой механики оплаты услуг на сайте.
Используемые библиотеки: pandas, requests, seaborn, matplotlib.pyplot, scipy.stats, numpy, chi2_contingency, chi2, norm.

Основные этапы проектов: 
1. Предварительный анализ данных (EDA), выявление зависимостей между данными;
2. Выбор данных, на основании которых будет проводится анализ результатов A/B-тестов;
3. Выбор и расчет метрик для анализа результатов A/B-тестов;
4. Выбор статистических тестов (t-тест, критерий Манна-Уитни, критерий хи-квадрат, метод bootstrap) для определения статистической значимости различий между показателями контрольной и целевой групп;
5. Вывод о необходимости раскатывать новую фичу на всех пользователей.
