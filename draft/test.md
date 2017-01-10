###定时器测试
	setTimeout(function () {
		    console.log("1");
		}, 0)
		console.log("2");  
		
	
	for (var i = 0;i<5;i++) {
		    setTimeout(function () {
		        console.log(i);    
		    }, 1000)
		};
		
		
	for(var i = 0; i < 5; i++) {
	    (function(i) {
	      setTimeout(function() {
	        console.log(i);  
	      }, 1000);
	    })(i)
	}
	
	

	