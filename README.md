# hello-haryward

$(document).on("click","#more-btn",function(){
	$dom = $(this).parent();
	$font = $(this).children();
	if($dom.hasClass("show-less")){
		$font.removeClass("icon-xialajiantouxiao");
		$font.addClass("icon-shouqijiantouxiao");
		
		$dom.removeClass("show-less");
		
	}else{
		$dom.addClass("show-less");
		$font.removeClass("icon-shouqijiantouxiao");
		$font.addClass("icon-xialajiantouxiao");
	}
	
})
