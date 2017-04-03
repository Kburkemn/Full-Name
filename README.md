# Full-Name
Function with arguments

function firstAndLast(given, family) {
  var fullName = given + ' ' + family;
	console.log('You\'re entire name is: ' + fullName);
}
var firstName = 'Kelly';
var lastName = 'Burke';
firstAndLast(firstName, lastName);


//Use return: use the function to set the value of a variable

function firstAndLast(given, family) {
  return given + ' ' + family;
	}
var firstName = 'Kelly';
var lastName = 'Burke';
console.log(firstAndLast(firstName, lastName));
