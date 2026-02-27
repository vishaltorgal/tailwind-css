# Tailwind CSS (2025–2026)

### Table of Contents

1. [Spacing](#1-spacing)
2. [Layout](#2-layout)
3. [Flexbox](#3-flexbox)
4. [Grid](#4-grid)
5. [Typography](#5-typography)
6. [Colors](#6-colors)
7. [Borders](#7-borders)
8. [Shadows](#8-shadows)
9. [Background](#9-background)
10. [Hover, Focus & States](#10-hover-focus--states)
11. [Responsive Design](#11-responsive-design)
12. [Transitions & Animations](#12-transitions--animations)


## 1. Spacing

### Margin
```jsx
m-4        /* margin all sides */
mt-4       /* margin top */
mb-4       /* margin bottom */
ml-4       /* margin left */
mr-4       /* margin right */
mx-4       /* margin left & right */
my-4       /* margin top & bottom */
```

### Padding

```jsx
p-4
pt-4
pb-4
pl-4
pr-4
px-4
py-4
```

***Common scale:***
```jsx
0, 1, 2, 3, 4, 5, 6, 8, 10, 12, 16, 20, 24, 32, 40, 48, 56, 64
```

***Example***
```jsx
<div class="m-8 p-6 bg-blue-100">
  <div class="mb-4 p-4 bg-blue-300">Box 1</div>
  <div class="mt-4 p-4 bg-blue-400">Box 2</div>
</div>
```

<br>


## 2. Layout

### Display
```jsx
block
inline-block
inline
flex
grid
hidden
```

### Width & Height
```jsx
w-full
w-screen
w-1/2
w-1/3
w-1/4
w-64

h-full
h-screen
h-64
```

### Position
```jsx
relative
absolute
fixed
sticky
top-0
left-0
right-0
bottom-0
z-10
```

***Example***
```jsx
<div class="relative h-40 bg-gray-200">
  <div class="absolute top-2 right-2 w-20 h-20 bg-red-500"></div>
</div>
```

<br>


## 3. Flexbox
```jsx
flex
flex-row
flex-col
flex-wrap
items-center
items-start
items-end
justify-center
justify-between
justify-around
gap-4
```

***Example***
```jsx
<div class="flex items-center justify-between p-4 bg-gray-100">
  <span>Left</span>
  <span>Right</span>
</div>
```

<br>

## 4. Grid
```jsx
grid
grid-cols-2
grid-cols-3
grid-cols-4
gap-4
col-span-2
row-span-2
```

***Example***
```jsx
<div class="grid grid-cols-3 gap-4 p-4">
  <div class="bg-blue-200 p-4">1</div>
  <div class="bg-blue-300 p-4">2</div>
  <div class="bg-blue-400 p-4">3</div>
</div>
```

<br>

## 5. Typography
```jsx
text-xs
text-sm
text-base
text-lg
text-xl
text-2xl
text-4xl

font-thin
font-light
font-normal
font-medium
font-semibold
font-bold

text-left
text-center
text-right

leading-tight
leading-normal
tracking-wide
```

***Example***
```jsx
<h1 class="text-3xl font-bold text-center mb-4">
  Tailwind Typography
</h1>

<p class="text-gray-600 leading-relaxed tracking-wide">
  This is a paragraph with proper spacing and readability.
</p>
```

<br>


## 6. Colors
```jsx
text-red-500
text-blue-600
bg-green-500
bg-gray-100
bg-black
bg-white
```

***Example***
```jsx
<div class="bg-green-500 text-white p-4 rounded-md">
  Success Message
</div>
```

### Opacity
```jsx
bg-black/50
text-red-500/75
```

***Example***
```jsx
<div class="bg-black/50 text-white p-4">
  Overlay effect
</div>
```

<br>

## 7. Borders
```jsx
border
border-2
border-t
border-b
border-red-500
rounded
rounded-md
rounded-lg
rounded-full
```

***Example***
```jsx
<div class="border-2 border-blue-500 rounded-lg p-4">
  Bordered Card
</div>
```

<br>

## 8. Shadows
```jsx
shadow-sm
shadow
shadow-md
shadow-lg
shadow-xl
```

***Example***
```jsx
<div class="shadow-lg p-6 rounded-lg bg-white">
  Elevated Card
</div>
```

<br>

## 9. Background
```jsx
bg-cover
bg-contain
bg-center
bg-no-repeat
bg-gradient-to-r
from-blue-500
to-purple-500
```

***Example: Gradient Background***
```jsx
<div class="bg-gradient-to-r from-blue-500 to-purple-600 text-white p-6">
  Gradient Section
</div>
```

***Example: Background image***
```jsx
<div class="bg-cover bg-center h-40"
     style="background-image: url('https://via.placeholder.com/400')">
</div>
```

<br>

## 10. Hover, Focus & States
```jsx
hover:bg-blue-500
hover:text-white
focus:outline-none
focus:ring-2
active:scale-95
disabled:opacity-50
```

***Example***
```jsx
<button class="px-4 py-2 bg-blue-500 text-white rounded-md
               hover:bg-blue-600
               focus:ring-2 focus:ring-blue-300
               active:scale-95
               transition">
  Click Me
</button>
```

<br>

## 11. Responsive Design
```jsx
sm:   /* ≥640px */
md:   /* ≥768px */
lg:   /* ≥1024px */
xl:   /* ≥1280px */
2xl:  /* ≥1536px */
```

***Example***
```jsx
<h1 class="text-sm md:text-lg lg:text-3xl">
  Responsive Heading
</h1>
```

<br>

## 12. Transitions & Animations
```jsx
transition
transition-all
duration-300
ease-in
ease-out
delay-200
```
### Transform:
```jsx
transform
scale-105
rotate-45
translate-x-4
```

***Example***
```jsx
<div class="w-40 h-40 bg-blue-400
            hover:scale-110
            transition
            duration-300
            ease-in-out">
</div>
```

<br>
