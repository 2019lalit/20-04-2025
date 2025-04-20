Order of Execution in Asynchronous JavaScript
What will be the output order of the following code in the console?

console.log("A");

setTimeout(() => {
  console.log("B");
}, 0); // Note the 0 millisecond delay

console.log("C");

answer- A
C
B
