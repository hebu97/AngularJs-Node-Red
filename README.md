# AngularJs-Node-Red

<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" >
		<meta name = "autor" content ="hebu97">
        <meta http-equiv = "refresh" content ="1000">
		
		<title>Test 2</title>
		
		
	</head>
	<body>
		<div id = "map"> Hallo </div>
		<div ng-bind-html="msg.payload"></div>
		<script src = "https://cdnjs.cloudflare.com/ajax/libs/raphael/2.1.0/raphael-min.js"> </script>
		<script src = "https://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"> </script>
		
		<script>
			

			
			
            ;(function(scope) {
                
                scope.$watch('msg.payload', function(newVal, oldVal) {
                    console.log('- Scope.msg -')
                    console.dir(scope.msg)
		    
		    data= msg.payload;
                    
                })
            
            })(scope)
			
			
		    
			
			
		</script>		
	</body>
</html>
