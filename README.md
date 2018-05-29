# jquery
Jquery short snippets

/* Jquery code for changing text and attr value when a particular class is there */
if(jQuery("body").hasClass("logged-in")){
	jQuery("li#menu-item-1853 a").text("Logout");
	jQuery("li#menu-item-1853 a").attr("href", "https://www.skywardimmigration.com/my-account-2/customer-logout/");
	}
