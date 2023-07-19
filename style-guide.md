# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
```

Material icon

``` html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@24,400,1,0" />
```

---

## CSS Variables

### Colors

``` css
--white: hsl(0, 0%, 100%);
--black: hsl(0, 0%, 0);
```

Dark colors

``` css
--background-dark: hsl(220, 40%, 13%);
--on-background-dark: hsl(0, 0%, 100%);
--primary-dark: hsl(212, 100%, 50%);
--primary-hover-dark: hsl(212, 100%, 45%);
--primary-outline-dark: hsl(212, 100%, 46%);
--primary-outline-hover-dark: hsl(212, 100%, 55%);
--surface-dark: hsl(222, 41%, 17%);
--on-surface-dark: hsl(223, 23%, 61%);
--on-surface-2-dark: hsl(222, 16%, 72%);
--surface-variant-dark: hsl(223, 40%, 20%);
--surface-variant-hover-dark: hsl(223, 40%, 24%);
--on-surface-variant-dark: hsl(223, 13%, 54%);
--surface-variant-outline-dark: hsl(222, 41%, 23%);
--surface-variant-outline-hover-dark: hsl(220, 40%, 40%);
--error-dark: hsl(0, 100%, 71%);
--error-alpha-10-dark: hsla(0, 100%, 71%, 0.1);
--outline-dark: hsl(223, 40%, 20%);
--surface-1-dark: hsl(220, 40%, 17%);
--surface-1-hover-dark: hsl(219, 40%, 21%);
--surface-1-outline-dark: hsl(219, 40%, 20%);
--surface-1-outline-hover-dark: hsl(220, 40%, 40%);
--alpha-80-dark: hsla(0, 0%, 100%, 0.8);
--alpha-70-dark: hsla(0, 0%, 100%, 0.7);
--alpha-60-dark: hsla(0, 0%, 100%, 0.6);
--alpha-50-dark: hsla(0, 0%, 100%, 0.5);
--alpha-10-dark: hsla(0, 0%, 100%, 0.1);
--alpha-5-dark: hsla(0, 0%, 100%, 0.05);
--overlay-bg-dark: hsla(220, 40%, 7%, 0.5);
```

Light colors

``` css
--background-light: hsl(0, 0%, 100%);
--on-background-light: hsl(220, 40%, 13%);
--primary-light: hsl(212, 100%, 50%);
--primary-hover-light: hsl(212, 100%, 45%);
--primary-outline-light: hsl(212, 100%, 46%);
--primary-outline-hover-light: hsl(212, 100%, 40%);
--surface-light: hsl(223, 100%, 96%);
--on-surface-light: hsl(222, 11%, 40%);
--on-surface-2-light: hsl(222, 11%, 36%);
--surface-variant-light: hsl(221, 26%, 89%);
--surface-variant-hover-light: hsl(221, 26%, 79%);
--on-surface-variant-light: hsl(223, 14%, 35%);
--surface-variant-outline-light: hsl(223, 18%, 85%);
--surface-variant-outline-hover-light: hsl(223, 18%, 75%);
--error-light: hsl(0, 54%, 49%);
--error-alpha-10-light: hsla(0, 54%, 49%, 0.1);
--outline-light: hsl(223, 10%, 83%);
--surface-1-light: hsl(223, 100%, 96%);
--surface-1-hover-light: hsl(223, 100%, 90%);
--surface-1-outline-light: hsl(223, 49%, 92%);
--surface-1-outline-hover-light: hsl(223, 49%, 82%);
--alpha-80-light: hsla(0, 0%, 0%, 0.8);
--alpha-70-light: hsla(0, 0%, 0%, 0.7);
--alpha-60-light: hsla(0, 0%, 0%, 0.6);
--alpha-50-light: hsla(0, 0%, 0%, 0.5);
--alpha-10-light: hsla(0, 0%, 0%, 0.1);
--alpha-5-light: hsla(0, 0%, 0%, 0.05);
--overlay-bg-light: hsla(220, 8%, 56%, 0.5);
```

### Typography

Font family

``` css
--font-primary: "Poppins", sans-serif;
```

Font size

``` css
--base-font-size: 62.5%;
--title-1: 4.8rem;
--title-2: 2.4rem;
--title-3: 1.8rem;
--body: 1.6rem;
--label-1: 1.4rem;
--label-2: 1.2rem;
```

Font weight

``` css
--weight-regular: 400;
--weight-medium: 500;
--weight-semiBold: 600;
--weight-bold: 700;
```

### Border Radius

``` css
--radius-8: 8px;
--radius-12: 12px;
--radius-24: 24px;
--radius-pill: 500px;
--radius-circle: 50%;
```

### Others

``` css
--header-height: 72px;
```

### Transition

``` css
--transition-timing-function: cubic-bezier(0.14, 0.97, 0.59, 1);
--transition-short: 150ms var(--transition-timing-function);
--transition-medium: 250ms var(--transition-timing-function);
--transition-long: 500ms var(--transition-timing-function);
```
