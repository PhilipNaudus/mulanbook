// From https://stackoverflow.com/questions/8425701/ajax-mailchimp-signup-form-integration

$(function() {
  $('form').ajaxChimp({
    callback: function(response) {
      //$('form .result').text(response.msg);
      alert(response.msg);
    }
  });
})



/*alert("welcome");

$('form').submit(function(e) {
  var $this = $(this);
  $.ajax({
      type: "GET", // GET & url for json slightly different
      url: "https://mulanbook.us20.list-manage.com/subscribe/post?u=f25c7fab2996d1b93cf488de8&amp;id=54faee06f6&amp;c=?",
      data: $this.serialize(),
      dataType    : 'json',
      contentType: "application/json; charset=utf-8",
      error       : function(err) { alert("Could not connect to the registration server."); },
      success     : function(data) {
          if (data.result != "success") {
              // Something went wrong, parse data.msg string and display message
	      alert(data.msg);
          } else {
              // It worked, so hide form and display thank-you message.
	      alert("hi!");
          }
      }
  });
  return false;
});
*/
