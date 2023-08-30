# AB_tests
В данном проекте проведен анализ результатов A/B-тестирования новой механики оплаты услуг на сайте. Дополнительно реализованы функции, позволяющие подгружать новую информацию об эксперименте, пересчитывать метрики с учетом новой информации и строить графики по полученным метрикам.  

Основные этапы: 
1. предварительный анализ данных (EDA), выявление зависимостей между данными;
2. выбор данных, на основании который будет проводится анализ результатов A/B-тестов;
3. выбор и расчет метрик для анализа результатов A/B-тестов;
4. выбор статистического теста (t-тест, критерий Манна-Уитни, критерий хи-квадрат, метод bootstrap) для определения статистической значимости различий между показателями контрольной и тестовой групп;
5. вывод о необходимости раскатывать новую механику оплаты услуг на всех пользователей.
