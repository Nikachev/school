# Trigonometry

| |$$\frac{\pi}{6}$$|$$\frac{\pi}{4}$$|$$\frac{\pi}{3}$$|
| --- | --- | --- | --- |
|$$sin$$|$$\frac{1}{2}$$|$$\frac{\sqrt{2}}{2}$$|$$\frac{\sqrt{3}}{2}$$|
|$$cos$$|$$\frac{\sqrt{3}}{2}$$|$$\frac{\sqrt{2}}{2}$$|$$\frac{1}{2}$$|
|$$tg$$|$$\frac{\sqrt{3}}{3}$$|$$1$$|$$\sqrt{3}$$|
|$$ctg$$|$$\sqrt{3}$$|$$1$$|$$\frac{\sqrt{3}}{3}$$|

$$1^\circ = \frac{\pi}{180}$$

## Основные соотношения

$$sin^2\alpha + cos^2\alpha = 1$$
$$tg\alpha = \frac{sin\alpha}{cos\alpha},\alpha \ne \frac{\pi}{2}+ \pi k, k \in \mathbb{Z}$$
$$ctg\alpha = \frac{cos\alpha}{sin\alpha}, \alpha \ne \pi k, k \in \mathbb{Z}$$
$$tg\alpha \cdot ctg\alpha = 1, \alpha \ne \frac{\pi k}{2}, k \in \mathbb{Z}$$
$$1 + tg^2\alpha = \frac{1}{cos^2\alpha}, \alpha \ne \frac{\pi}{2} + \pi k, k \in \mathbb{Z}$$
$$1 + ctg^2\alpha = \frac{1}{sin^2\alpha}, \alpha \ne \pi k, k \in \mathbb{Z}$$

## Формулы приведения

|$$\beta$$|$$\frac{\pi}{2} + \alpha$$|$$\pi + \alpha$$|$$\frac{3 \pi}{2} + \alpha$$|$$\frac{\pi}{2} - \alpha$$|$$\pi - \alpha$$|$$\frac{3 \pi}{2} - \alpha$$|$$2 \pi - \alpha$$|
| --- | --- | --- | --- | --- | --- | --- | --- |
|$$sin\beta$$|$$cos\alpha$$|$$-sin\alpha$$|$$-cos\alpha$$|$$cos\alpha$$|$$sin\alpha$$|$$-cos\alpha$$|$$-sin\alpha$$|
|$$cos\beta$$|$$-sin\alpha$$|$$-cos\alpha$$|$$sin\alpha$$|$$sin\alpha$$|$$-cos\alpha$$|$$-sin\alpha$$|$$cos\alpha$$|
|$$tg\beta$$|$$-ctg\alpha$$|$$tg\alpha$$|$$-ctg\alpha$$|$$ctg\alpha$$|$$-tg\alpha$$|$$ctg\alpha$$|$$-tg\alpha$$|
|$$ctg\beta$$|$$-tg\alpha$$|$$ctg\alpha$$|$$-tg\alpha$$|$$tg\alpha$$|$$-ctg\alpha$$|$$tg\alpha$$|$$-ctg\alpha$$|

При целом $\pi$ функция остаётся неизменной, при полуцелом $\pi$ функция меняется на родственную.

Полученная функция будет иметь знак исходной функции в этой четверти при $0<\alpha<\frac{\pi}{2}$.

## Формулы суммы и разности

$$sin(\alpha + \beta) = sin\alpha cos\beta + cos\alpha sin\beta$$
$$sin(\alpha - \beta) = sin\alpha cos\beta - cos\alpha sin\beta$$
$$cos(\alpha + \beta) = cos\alpha cos\beta - sin\alpha sin\beta$$
$$cos(\alpha - \beta) = cos\alpha cos\beta + sin\alpha sin\beta$$
$$tg(\alpha + \beta) = \frac{tg\alpha + tg\beta}{1 - tg\alpha tg\beta}$$
$$tg(\alpha - \beta) = \frac{tg\alpha - tg\beta}{1 + tg\alpha tg\beta}$$

## Формулы двойного аргумента

$$sin2\alpha = 2 sin\alpha cos\alpha$$
$$cos2\alpha = cos^2\alpha - sin^2\alpha$$
$$tg2\alpha = \frac{2tg\alpha}{1 - tg^2\alpha}$$

## Формулы понижения степени (половинного аргумента)

$$cos^2\frac{\alpha}{2} = \frac{1 + cos\alpha}{2}$$
$$sin^2\frac{\alpha}{2} = \frac{1 - cos\alpha}{2}$$
$$tg^2\frac{\alpha}{2} = \frac{1 - cos\alpha}{1 + cos\alpha}$$

## Преобразование суммы в произведение

$$sin\alpha + sin\beta = 2 sin\frac{\alpha + \beta}{2} cos\frac{\alpha - \beta}{2}$$
$$sin\alpha - sin\beta = 2 cos\frac{\alpha + \beta}{2} sin\frac{\alpha - \beta}{2}$$
$$cos\alpha + cos\beta = 2 cos\frac{\alpha + \beta}{2} cos\frac{\alpha - \beta}{2}$$
$$cos\alpha - cos\beta = -2 sin\frac{\alpha + \beta}{2} sin\frac{\alpha - \beta}{2}$$

## Преобразование произведения в сумму

$$sin\alpha cos\beta = \frac{sin(\alpha + \beta) + sin(\alpha - \beta)}{2}$$
$$cos\alpha cos\beta = \frac{cos(\alpha + \beta) + cos(\alpha - \beta)}{2}$$
$$sin\alpha sin\beta = \frac{cos(\alpha - \beta) - cos(\alpha + \beta)}{2}$$

## Метод введения вспомогательного угла

$$A \cdot sin\alpha + B \cdot cos\alpha = C \cdot sin(\alpha + \beta)$$
$$C = \sqrt{A^2 + B^2}$$
$$\frac{A}{B} = tg\beta$$
$$\frac{A}{C} = cos\beta$$
$$\frac{B}{C} = sin\beta$$

## Обратные функции

$cos\alpha = x, x \in [-1;1] \\
\alpha = \pm arccos x + 2 \pi k, k \in \mathbb{Z}$

$arccos x + arccos(-x) = \pi$

$sin\alpha = x, x \in [-1;1] \\
\alpha = (-1)^k arcsin x + \pi k, k \in \mathbb{Z}$

$arcsin(-x) = -arcsin x$

$tg\alpha = x \\
\alpha = arctg x + \pi k, k \in \mathbb{Z}$

$arctg(-x) = -arctg x$

$ctg\alpha = x \\
\alpha = arcctg x + \pi k, k \in \mathbb{Z}$

$arcctg x + arcctg(-x) = \pi$
