var arr = ['  Apple', 'Mango', 'Banana', 'Strawberry   '];
arr = arr.map(function(str) {
  return str.trim(); 
});
console.log(arr); // Output: ["Apple", "Mango", "Banana", "Strawberry"]
