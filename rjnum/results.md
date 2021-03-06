# Результаты

Приведем резульаты некоторых результатов, полученных в рамках данной работы.
Расчеты проводились для случаев постоянной и переменной плотности и вязкости в
безразмерных величинах. Для клапана использовались две геометрии - идеальный клапан
упрощенной формы и клапан, полученный сканированием реального биопротеза
"Юнилайн" [@клышников2013сравнительная]. В качестве сосуда для всех расчетов
используется круговой цилиндр с длинной $l=1$, радиусом $r=0.11$ и жесткостью
стенок $k=1 \cdot 10^{3}$. Для створок клапана заданы коэффициенты
сопротивления растяжению $k_s = 5  \cdot 10^{3}$ и скручиванию $k_b = 2 \cdot
10^{3}$. Перепад давления $p_{in} - p_{out}$ периодически меняется от 0 до 6.
Область $\tilde{\Omega}$ имеет параметры $10 \times 0.5 \times 0.5$, шаги по
пространственной сетке $\tilde{\Omega_h}$ $h_x = h_y = h_z = 0.01$, шаг по
времени $\triangle t = 0.01$.

На рис. [@fig:ideal_valve_stress] показана динамика движения одного лепестка
идеального трехстворчатого клапана под воздействием жидкости с постоянной
вязкостью и плотностью $\rho_1=\rho_2=1, \mu_1=\mu_2=1 \cdot 10^{-2}$, а также
распределение напряжения по поверхности.

![](ideal_valve_stress_1.png)

![](ideal_valve_stress_2.png)

![Распределение напряжение по поверхности лепестка во времена t=0, t=0.4, t=0.8. Точками обозначены стенки сосуда](ideal_valve_stress_3.png) {#fig:ideal_valve_stress}

Как видно из рис. [@fig:ideal_valve_stress], больше поверхностного напряжения возникает в
двух областях - на конце лепестка, т.к. это самая гибкая его часть, которая
подвержена наибольшим деформациям скручивания, и в области крепления лепестка к
фиброзному кольцу, т.к. там возникает наибольшая деформация растяжения в силу
фиксированного расположения.

На рис. [@fig:uniline_dynamics] представлена динамика движения для клапана
"Юнилайн", который двигается под воздействием движения жидкости с постоянной
вязкостью и плотностью $\rho_1=\rho_2=1, \mu_1=\mu_2=1 \cdot 10^{-2}$.

![](uniline_dynamics_11.png)

![](uniline_dynamics_22.png)

![Работа клапана во времена t=0, t=0.5, t=1.8. Точками обозначена поверхность
фиброзного кольца и лепестков клапана](uniline_dynamics_33.png)
{#fig:uniline_dynamics}

На рис. [@fig:uniline_stress] представлена динамика движения и распределение поверхностного
напряжения для лепестка клапана "Юнилайн", который двигается под воздействием движения
жидкости с постоянной вязкостью и плотностью $\rho_1=\rho_2=1, \mu_1=\mu_2=1 \cdot 10^{-2}$.

![](uniline_stress_1.png)

![](uniline_stress_2.png)

![Распределение напряжение по поверхности лепестка во времена t=0, t=0.4, t=0.8. Точками обозначена поверхность фиброзного кольца](uniline_stress_3.png) {#fig:uniline_stress}


Рис. [@fig:uniline_stress] показывает небольшую ассиметрию распределения напряжения,
связанную с исходной ассиметрией клапана. Помимо этого, в отличии от клапана
идеальной формы, в области крепления лепестка к фиброзному кольцу не
происходит значительного увеличения напряжения.

![Схема расположения точек на фиброзном кольце](valve_points.png) {#fig:points_scheme}

На рис. [@fig:fibrouse_forces] показано графики зависимости поверхностного
напряжения от времени для трех точек в разных частях фиброзного кольца.
"Активная точка" находится на одной из осей кольца, рядом с областью крепления
лепестка. "Точка на границе" тоже располагается в области крепления, но на
удалении от осей. "Пассивная точка" располагается на внешней, наименее
подвижной части кольца (см. рис. [@fig:points_scheme]).

![Зависимость напряжения от времени для трех точек на фиброзном кольце](forces.png) {#fig:fibrouse_forces}

Как видно из рис. [@fig:fibrouse_forces], качественно величина напряжения для каждой
точки демонстрирует схожую динамику изменения, но при этом в области
крепления и рядом с осями возникают большие напряжения.

На рис. [@fig:pressure_limit] продемонстрировано, что в данной
конфигурации при завершении цикла работы клапан эффективно является закрытым,
т.к. в области его расположения резко изменяется давление и скорость.

![Резкий перепад давления при закрытии клапана, точками обозначена поверхность фиброзного кольца](pressure_limit.png) {#fig:pressure_limit}
