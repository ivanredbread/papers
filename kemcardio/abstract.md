# Математическое моделирование работы искусственного сердечного клапана

Долгов Дмитрий Андреевич, аспирант, Кемеровский Государственный Университет, e-mail: 9erthalion6@gmail.com

В последние годы, в связи с развитием новых методов лечения различных патологий
сердечно-сосудистой системы, существенно возрос интерес к математическому
моделированию движения крови в сосудах и искусственных сердечных клапанах
человека. Искусственный сердечный клапан - чрезвычайно сложная система, к
работе которой предъявляется множество требований, поэтому математическое
моделирование существенно упрощает процесс его разработки и оптимизации
структуры. В данной работе мы предлагаем математическую модель для описания
трехмерной динамики течения крови в крупных кровеносных сосудах и искусственном сердечном
клапане, а также численный метод решения данной задачи. Исследование проводится
в рамках проектной части госзадания № 1.630.1.2014/K.

Предложенная для решения нестационарной задачи о течении крови внутри клапана
математическая модель позволяет учитывать основные особенности функционирования
сердечного клапана: неоднородную структуру крови, а также гибкость лепестков
клапана, их сложную форму и чрезвычайную тонкость. Кровь моделируем как вязкую
несжимаемую неоднородную жидкость, состоящую из двух компонент
(соответствующих, например, плазме и форменным элементам). Ее движение описываем с помощью
нестационарной системой дифференциальных уравнений Навье-Стокса с переменными
вязкостью и плотностью, где концентрация примеси описывается уравнением
конвекции. Лепесток клапана моделируем как гибкую непроницаемую поверхность,
которая деформируется под воздействием давления крови. Деформацию лепестков, а
также их взаимодействие с жидкостью описываем с помощью метода погруженной
границы, учитывая влияние лепестков на течение с помощью добавления массовых
сил в уравнение движения жидкости.

Описанная математическая модель и численный метод решения могут быть применены
для решения широкого круга медицинских задач. Задавая в качестве начальных
данных перепад давления, форму сосуда и лепестков клапана, а также начальное
распределение примесей в крови, можно определить динамику описанной
биологической системы, включая расход жидкости в сосуде, геометрию лепестков
клапана и их напряжение деформации в любой момент времени и распределение
примеси в крови.
