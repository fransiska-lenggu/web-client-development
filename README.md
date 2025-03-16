# web-client-development
function fahrenheitToCelsius(fahrenheit) {
    return (fahrenheit - 32) * 5 / 9;
}

console.log(fahrenheitToCelsius(100));

task 2
function convertLength(value, unit) {
    if (unit === "cm") {
        return value / 100000 + " km";
    } else if (unit === "km") {
        return value * 100000 + " cm";
    } else {
        return "Invalid unit";
    }
}

console.log(convertLength(100000, "cm")); // Output: "1 km"
console.log(convertLength(1, "km")); 

task 3
function isEven(n) {
    return n % 2 === 0;
}

console.log(isEven(1000)); 
console.log(isEven(1001)); 

task 4
function removeFirstOccurrence(str, search) {
    return str.replace(search, '');
}

console.log(removeFirstOccurrence("Hello world", "ell")); 

task 5
function isPalindrome(str) {
    let reversed = str.split('').reverse().join('');
    return str === reversed;
}

console.log(isPalindrome("madam"));
console.log(isPalindrome("hello"));
