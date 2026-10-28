# bilal-.js
let a = 10, b = 5;

console.log("Addition =", a + b);
console.log("Subtraction =", a - b);
console.log("Multiplication =", a * b);
console.log("Division =", a / b);
console.log("Modulus =", a % b);
let a = 10, b = 5;

console.log("Equal =", a === b);
console.log("Not Equal =", a !== b);
console.log("Greater =", a > b);
console.log("Less =", a < b);
console.log("Greater or Equal =", a >= b);
console.log("Less or Equal =", a <= b);
let n = 8;

if (n > 0) {
    console.log("Number is positive");
} else {
    console.log("Number is not positive");
}let n = 7;

if (n % 2 === 0) {
    console.log("Even number");
} else {
    console.log("Odd number");
}

let a = true, b = false;

console.log("AND =", a && b);
console.log("OR =", a || b);
console.log("NOT =", !a);
let age = 20;

if (age >= 18) {
    console.log("Eligible to vote");
} else {
    console.log("Not eligible to vote");
}let n = -5;

if (n > 0) {
    console.log("Positive number");
} else if (n < 0) {
    console.log("Negative number");
} else {
    console.log("Zero");

let marks = 85;

if (marks < 0 || marks > 100) {
    console.log("Invalid marks");
} else if (marks >= 90) {
    console.log("Grade A");
} else if (marks >= 80) {
    console.log("Grade B");
} else if (marks >= 70) {
    console.log("Grade C");
} else if (marks >= 60) {
    console.log("Grade D");
} else if (marks >= 40) {
    console.log("Grade E");
} else {
    console.log("Grade F");
}
}
let a = 10, b = 20;

if (a > b) {
    console.log(a + " is largest");
} else if (b > a) {
    console.log(b + " is largest");
} else {
    console.log("Both numbers are equal");
}
let year = 2024;

if (year % 400 === 0 ||
    (year % 4 === 0 && year % 100 !== 0)) {
    console.log("Leap year");
} else {
    console.log("Not a leap year");
}
for (let i = 1; i <= 10; i++) {
    console.log(i);
}
let n = 5;

for (let i = 1; i <= 10; i++) {
    console.log(n + " x " + i + " = " + (n * i));
}
let n = 5;
let sum = 0;

for (let i = 1; i <= n; i++) {
    sum = sum + i;
}

console.log("Sum =", sum);
for (let i = 2; i <= 50; i += 2) {
    console.log(i);
}
let count = 0;

for (let i = 1; i <= 100; i++) {
    if (i % 3 === 0) {
        count++;
    }
}

console.log("Count =", count);
let a = 10, b = 25, c = 15;

if (a >= b && a >= c) {
    console.log(a + " is largest");
} else if (b >= a && b >= c) {
    console.log(b + " is largest");
} else {
    console.log(c + " is largest");
}
let n = 30;

if (n % 3 === 0 && n % 5 === 0) {
    console.log("Divisible by both 3 and 5");
} else {
    console.log("Not divisible by both 3 and 5");
}
let n = 5;
let fact = 1;

if (!Number.isInteger(n) || n < 0) {
    console.log("Enter a non-negative integer");
} else {
    for (let i = 1; i <= n; i++) {
        fact = fact * i;
    }

    console.log("Factorial =", fact);
}
for (let i = 50; i >= 1; i--) {
    console.log(i);
}
let sum = 0;

for (let i = 1; i <= 100; i += 2) {
    sum = sum + i;
}

console.log("Sum of odd numbers =", sum);