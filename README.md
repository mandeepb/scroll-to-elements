
function scrollTo($element) {
  $('body, html').animate({
		scrollTop: $element.offset().top - 20, 500
	});
}
