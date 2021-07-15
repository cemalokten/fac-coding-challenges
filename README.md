# fac-coding-challenges

## FAC Pre-apprenticeship Coding Challenges

A collection of coding challenges created over the 12 week Founders and Coders pre-apprenticeship 2021

# 🏀 Week One 

### 🚀 Coding Challenges (for..of)

The following coding challenges should be completed without using `.map()` `.filter()` `.reduce()` `.forEach()` and `.find()`

Write a function that `filters` only the counties which include *'shire'* into a new array.

```js
let counties = ['Avon', 'Bedfordshire', 'Berkshire', 'Buckinghamshire', 'Cambridgeshire', 'Cheshire', 'Cleveland', 'Cornwall', 'Cumbria', 'Derbyshire', 'Devon', 'Dorset', 'Durham', 'East-Sussex', 'Essex', 'Gloucestershire', 'Hampshire', 'Herefordshire', 'Hertfordshire', 'Isle-of-Wight', 'Kent', 'Lancashire', 'Leicestershire', 'Lincolnshire', 'London', 'Merseyside', 'Middlesex', 'Norfolk', 'Northamptonshire', 'Northumberland', 'North-Humberside', 'North-Yorkshire', 'Nottinghamshire', 'Oxfordshire', 'Rutland', 'Shropshire', 'Somerset', 'South-Humberside', 'South-Yorkshire', 'Staffordshire', 'Suffolk', 'Surrey', 'Tyne-and-Wear', 'Warwickshire', 'West-Midlands', 'West-Sussex', 'West-Yorkshire', 'Wiltshire', 'Worcestershire'];
```

# 🌋 Week Three 

### 🚀 Coding Challenges (for..of) Continued...
The following coding challenges should be completed without using `.map()` `.filter()` `.reduce()` `.forEach()` and `.find()`

I went to the supermarket and bought some fruit 🍊, I recorded the items and their cost in an array. Using a `for..of` loop return the total cost, in the following format : `£10,00'

```js
let supermarketShop = [["Banana", '£3'], ["Apple", '£4'], ["Orange", '£5.23'], ["Peach", '£6.02'], ["Pineaple", '£5.00']];
```

# 🛰 Week Four 

### 🚀 Coding Reading Challenges
The following code reading challenges are intentionally abstracted, the variable names do not have a meanings. Talk through the code and what it does, what does it return?

Each Challenge is slightly harder than the previous.

#### **Challenge 1 - What does this function return?**

```js
function a() {
	let b = 1;
	if (true) {
		let b = 2;
	}
	return b;
}

a();
```

#### **Challenge 2 - What does this function return?**

```js
const n = function(a) {
	return Object.keys(a);
};

n([ 1, 2, '%', '!' ]);
```

#### **Challenge 3 - What does this function return?**

```js
const array = [];

function r(a) {
	a[3] = 'a';
	const n = [];
	for (const k in a) {
		n.push(k);
	}
	n;
}

r(array);
```
