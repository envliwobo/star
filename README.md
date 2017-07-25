
	<script>
	// for(var i=1;i<10;i++){
	// 	for (var j = 1; j <=i; j++) {
	// 		if(j==1){
	// 			var a=j+'*'+i;
	// 		}
	// 		if(j==2){
	// 			var a1=j+'*'+i;
	// 		}
	// 		if(j==3){
	// 			var a2=j+'*'+i;
	// 		}
	// 		if(j==4){
	// 			var a3=j+'*'+i;
	// 		}
	// 		if(j==5){
	// 			var a4=j+'*'+i;
	// 		}
	// 		if(j==6){
	// 			var a5=j+'*'+i;
	// 		}
	// 	}	
	// 	console.log(a+" "+a1+" "+a2+" "+a3+" "+a4+" "+a5);
	// }


	// for(var i=1;i<10;i++){
	// 	var aa=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	console.log(aa);
	// }	
	// console.log(" ");
	// for(var i=9;i>=1;i--){
	// 	var aa=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	console.log(aa);
	// }	
	// console.log(" ");
	// for(var i=9;i>=1;i--){
	// 	var aa=" ";
	// 	var a2=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	if(i<9){
	// 		var a1 = 0;
	// 		a1=9-i;
	// 		for(var k=0;k<a1;k++){
	// 			a2+="  ";
	// 		}
	// 	}
	// 	console.log(a2+aa);
	// }	
	// console.log(" ");
	// for(var i=1;i<=9;i++){
	// 	var aa=" ";
	// 	var a2=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	if(i<9){
	// 		var a1 = 0;
	// 		a1=9-i;
	// 		for(var k=0;k<a1;k++){
	// 			a2+="  ";
	// 		}
	// 	}
	// 	console.log(a2+aa);
	// }
	// console.log(" ");
	// for(var i=1;i<=9;i++){
	// 	var aa=" ";
	// 	var a2=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	if(i<9){
	// 		var a1 = 0;
	// 		a1=9-i;
	// 		for(var k=0;k<a1;k++){
	// 			a2+="    ";
	// 		}
	// 	}
	// 	console.log(a2+aa);
	// }
	// console.log(" ");
	// for(var i=9;i>=1;i--){
	// 	var aa=" ";
	// 	var a2=" ";
	// 	for (var j = 1; j<=i; j++) {
	// 		aa+=j+'*'+i+" ";
	// 	}
	// 	if(i<9){
	// 		var a1 = 0;
	// 		a1=9-i;
	// 		for(var k=0;k<a1;k++){
	// 			a2+="    ";
	// 		}
	// 	}
	// 	console.log(a2+aa);
	// }

	for(var i=1;i<=18;i++){
		var aa=" ";
		var a2=" ";
		var h=i;
		if(i>9){
			var	h=i-9;
			h=9-h;
		}
		for (var j = 1; j<=h; j++) {
			aa+=j+'*'+h+" ";
		}
		if(h<9){
			var a1 = 0;
			a1=9-h;
			for(var k=0;k<a1;k++){
				a2+="  ";
			}
		}
		console.log(a2+aa);
	}
	</script>
