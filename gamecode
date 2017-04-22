
function myFunction(rating){
	console.log(rating);
	var currentPicture = document.getElementById("image1");
//Picks a random number from 1 - 10
	var nextPictureNumber = Math.floor(Math.random() * (10 - 1 + 1)) + 1;
	console.log(nextPictureNumber);

	currentPicture.src = "litterimage" + nextPictureNumber + ".jpg";


}

var isopen = false;

function sidebarFunction(){
	console.log("correct");
	var sidebarImage = document.getElementById("swipebar");
	var closetab = document.getElementById("lebutton");
	
	if(isopen) {
		isopen = false;
		closetab.innerHTML = "<~~ Examples of levels";
		sidebarImage.className = "sidebar";
		
	}

	else{
		isopen = true;
		closetab.innerHTML = "~~> Close";
		sidebarImage.className = "sidebar visiblebar";

	}
	
}

