###定位偏移量（right）
	auto
		Is a keyword that represents:
		是个关键字，它表示：
		
		for absolutely positioned elements, the position the element based on the
		left property and treat width: auto as a width based on the content.
		对于绝对定位元素，元素位置根据left 属性和width宽度计算，宽度是auto时要根据内容计算。
		
		for relatively positioned elements, the right offset the element 
		from its original position based on the left property, or if left is also auto, do not offset it at all.
		对于相对定位元素，根据元素的原始位置和left 属性计算右偏移值，如果left属性也是auto，
		则都没有偏移。则都为0
		
		
		当right和left同时出现，并且 width没定义或者为auto或100%的时候，right和left都会生效，
		在其他情况下，如果 width被限制，则left属性会优先设置right属性会被忽略。
		
###绝对定位盒子的特性
	absolute性质的盒子，它的包含块的宽度等于它的盒模型的宽度 + left + right值，包含块的高度同理，