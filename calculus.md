# Calculus

## Пределы

$$\lim_{x \to \infty} C = C$$
$$\lim_{x \to \infty} \frac{k}{x^m} = 0$$

Если

$$\lim_{x \to \infty} f(x) = b,$$
$$\lim_{x \to \infty} g(x) = c,$$

то

$$\lim_{x \to \infty} (k f(x)) = kb$$
$$\lim_{x \to \infty} |f(x)| = |b|$$
$$\lim_{x \to \infty} (f(x) + g(x)) = b + c$$
$$\lim_{x \to \infty} (f(x)g(x)) = bc$$
$$\lim_{x \to \infty} \frac{f(x)}{g(x)} = \frac{b}{c}$$

## Производные

### Формулы дифференцирования

$$(C)' = 0$$
$$(x^a)' = a x^{a-1}$$
$$(a^x)' = a^x ln a$$
$$(log_a x)' = \frac{1}{x ln a}$$
$$(sin x)' = cos x$$
$$(cos x)' = -sin x$$
$$(tg x)' = \frac{1}{cos^2 x}$$
$$(ctg x)' = -\frac{1}{sin^2 x}$$
$$(arcsin x)' = \frac{1}{\sqrt{1 - x^2}}$$
$$(arccos x)' = -\frac{1}{\sqrt{1 - x^2}}$$
$$(arctg x)' = \frac{1}{1 + x^2}$$
$$(arcctg x)' = -\frac{1}{1 + x^2}$$

### Правила дифференцирования

$$(f(x) + g(x))' = f'(x) + g'(x)$$
$$(k f(x))' = k f'(x)$$
$$(f(x)g(x))' = f'(x)g(x) + f(x)g'(x)$$
$$\left( \frac{f(x)}{g(x)} \right)' = \frac{f'(x)g(x) - f(x)g'(x)}{g^2(x)}$$

### Дифференцирование сложной функции

$$(f(g(x)))' = f'(g(x)) g'(x)$$

Для вычисления производной произведения нескольких функция или степени, в которой основание и показатель степени являются функциями:

$$(f(x))' = f(x)(ln f(x))'$$

### Производная n-го порядка

$$f''(x) = f^{(2)}(x) = \frac{d^2 y}{d x^2}$$
$$f^{(n)}(x) = \frac{d^n y}{d x^n}$$

### Уравнение касательной

$$y = f(a) + f'(a)(x - a)$$

## Интегралы

### Таблица интегралов

$$\int C dx = C x + C_1$$
$$\int x^a dx = \frac{x^{a+1}}{a+1} + C, n \ne -1$$
$$\int \frac{dx}{x} = ln |x| + C$$
$$\int a^x dx = \frac{a^x}{ln a} + C$$
$$\int \frac{1}{a^x} dx = -\frac{1}{a^x ln a} + C$$
$$\int sin x dx = -cos x + C$$
$$\int cos x dx = sin x + C$$
$$\int \frac{dx}{cos^2 x} = tg x + C$$
$$\int \frac{dx}{sin^2 x} = -ctg x + C$$
$$\int \frac{dx}{\sqrt{a^2 - x^2}} = arcsin \frac{x}{a} + C$$
$$\int \frac{dx}{\sqrt{k + x^2}} = ln |x + \sqrt{k + x^2}| + C$$
$$\int \frac{dx}{x^2 + a^2} = \frac{1}{a} arctg \frac{x}{a} + C$$
$$\int \frac{dx}{x^2 - a^2} = \frac{1}{2a} ln \left| \frac{x - a}{x + a} \right| + C$$

### Правила интегрирования

$$\int F'(x) dx = F(x) + C$$
$$\int k f(x) dx = k \int f(x) dx$$
$$\int (f(x) + g(x)) dx = \int f(x) dx + \int g(x) dx$$

### Метод замены переменной

$$x = g(t)$$
$$dx = g'(t) dt$$

### Метод интегрирования по частям

$$\int u dv = uv - \int v du$$

### Определенный интеграл

$$\int_a^b f(x) dx = \left. F(x) \right|_a^b = F(b) - F(a)$$
