lets give this a go!
https://scotch.io/tutorials/easy-node-authentication-setup-and-local

facebook stuff
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId      : '984653148253651',
      xfbml      : true,
      version    : 'v2.4'
    });
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "//connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>

-- App Secret = 20fa5174dc202a48640421741492831a