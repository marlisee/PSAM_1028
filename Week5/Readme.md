``` ruby
// functions
// most basic function
// function declaration/definition

var ourFirstFunction = function(){

console.log("Hello world")

} 

//call function

ourFirstFunction

//



var sayHello = function(){
 console.log("hello" + "you")


}

//arguement in function

var sayHello = function(username){
	console.log("hello" + "username")
}

sayHello("TM")


// or

var sayHello = function(){
    var username = "TM" 
    console.log("Hello" + username ) }




 var drawCats = function(howManyTimes){
 for (var i = 0; i < howManyTimes; i++)
 {

console.log(i + "=^.^=")

 }
 }







var functionMultipleTimes = function(howManyTimes, whatToDraw){
	
	for(var i = 0; i < howManyTimes; i++){
	console.log(i + " " + whatToDraw)
	}
}



var drawThreeCats = functions (){	

console.log("Before Return")

retunrn // leaves function

console.log("After Return")

}




var triple = function(passedNumberArgument){
	
	var x = passedNumberArgument * 3 

	return x 

}


var fifthLetter = function(name){
	
if(name.length < 5){
	
	return "Sorry Your Name is Too Short, try a longer one"

}

return "The Fifth Letter of Your Name is " + name[4] + "."


}



var gradeForScore = function(score){

	if (score >= 90){
	return "A"

	}
if (score < 90 && score > 80){
	return "B"
	}

	if(score < 90 && score > 70){
	return "C"
	}

	if(score < 90 && score > 60){
	return "D"
	}

	if(score < 90 && score > 0){
	return "F"
	}


}

```
