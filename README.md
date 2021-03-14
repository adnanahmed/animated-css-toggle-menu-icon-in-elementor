# animated-css-toggle-menu-icon-in-elementor
Simple CSS and JQuery code for creating animated css toggle menu icon in elementor.
====================


<style>
.menu-section{
    display: none;
}
body.menu-active .menu-section{
    display:block;
}
.menu-click i{
    transition: .3s;
}
body.menu-active .menu-click .elementor-icon i{
    transform: rotate(45deg) !important;
	color:#fff;
}
</style>



<script>
	jQuery(document).ready(function($){
	$('.menu-click').click(function(){
		$('body').toggleClass('menu-active');
	});
});
</script>



In this video, I am going to create a button to show and hide  the navigation menu bar.

As you can see on the screen, when I am clicking this plus icon, it showing the menu and the icon is changing to cross. And when clicking again it is hiding the menu and the icon is changed back to plus icon.

So it is a toggle action which is happening on the button. 

And For this I am going to use a simple CSS. 

Today I am going to create the Animated Menu Button to show and hide the header menu. 


And this I am going to do in Elementor. I am going to use the Free version. 

Check the complete video here. https://youtu.be/vCNSgRJnjyc
