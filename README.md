# Javascript-Complete
Javascript Examples


const numbers = [1, 2, 3, 4];
const halves = numbers.map(x => x * 2);
console.log(halves)  

const words = ["Rajendra", "Ramdas", "Vipul", "Rahul", "Sunil", "Atul"];

const longWords = words.filter(word => word.length > 6);

console.log(longWords)   

const total = [6, 7, 8, 9].reduce((sum, value) => sum + value, 1);

console.log(total)   
 
const x = { c:6,d:8};
const y = {a: 1, b: 2};
const z = Object.assign({}, x, y);
 
 console.log(x)
 console.log(y)  
 console.log(z)  
 
const x1 = [1, 2,null, 3];
const y1 = [...x1, 4, 5];

console.log(y1); 
