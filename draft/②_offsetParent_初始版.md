###offsetParent
	1.本身定位不为fixed
		父级没有定位
			所有浏览器：==> offsetParent:body
		父级有定位
			所有浏览器：==> offsetParent:定位父级
			
		
	2.本身定位为fixed		
		非火狐		==> offsetParent:null
					
		火狐			==> offsetParent:body
					
	
					
###haslayout
	ie7以下,如果当前元素的某个父级触发了haslayout，
		那么offsetParent就会被指向到这个触发了layout特性的父节点上